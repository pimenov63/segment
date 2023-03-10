

Следующая ячейка кода может вызвать ошибку исполнения в Google Colab:
face_locations = face_recognition.face_locations(image, number_of_times_to_upsample = 3, model = 'cnn')
face_locations


Можно использовать один из способ решения:
1.  # Для использования CNN(model = 'cnn' ),т.е. без изменения кода, нужно откатить библиотеку dlib.
    добавить строку кода после установки face_recognition (!pip install face_recognition):

!pip install dlib==19.18.0

2.  # Можно примениить вызов другой модели (model = 'hog) 
    # тогда вызов примет вид face_recognition.face_locations(image, number_of_times_to_upsample = 3, model = 'hog')