

��������� ������ ���� ����� ������� ������ ���������� � Google Colab:
face_locations = face_recognition.face_locations(image, number_of_times_to_upsample = 3, model = 'cnn')
face_locations


����� ������������ ���� �� ������ �������:
1.  # ��� ������������� CNN(model = 'cnn' ),�.�. ��� ��������� ����, ����� �������� ���������� dlib.
    �������� ������ ���� ����� ��������� face_recognition (!pip install face_recognition):

!pip install dlib==19.18.0

2.  # ����� ���������� ����� ������ ������ (model = 'hog) 
    # ����� ����� ������ ��� face_recognition.face_locations(image, number_of_times_to_upsample = 3, model = 'hog')