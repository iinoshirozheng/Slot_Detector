# �۰ʿ��ѵP���{���ϥνd�� 

---
## �M�פ���

&emsp;&emsp;�ϥΦ۰ʿ��ѩ��Q�������{���i�H�ֳt�Ӧ��Ī��P�_�X���Q�����P���A�٥h��ʧP�_���ɶ��A�קK�H�����~�C�i�H���Φb�իٲ��~�B�C�����x���譱�A�j�T�����@�~�Ĳv�P���T�ʡC�ӵ{������Y���ѧO�X���Q�������U�عϮפΨ�ƦC�A����i�H�i�@�B�z�L�ƾڤ��R�A���ѧ�h���Ϊ���T�A�p RTP�BCV �ȵ����A���ϥΪ̧�e�����R�C�����x���]�w���v�C����ױM���]�p���A�Ω�U�ؤ��P���������Q���A�i�@�B�������ΩʡA�H�U���������ĪG�e�� :  

![Demo Detector Gif](./readme_src/Detector.gif)  

### --> �U���èϥΡA�I�����B�� [�d��](https://gitlab.uj.com.tw/ray1105/slot_detector_demo/-/archive/main/slot_detector_demo-main.zip?path=Demo) �ɮסC

---
## �ɮ��`��  
���B�|���ѨC���ɮת��@�ΥH�ΨC���ɮת��γ~�A�åB�b�᭱�� [�ϥλ���](#�ϥλ���) ���Բӻ����p��ާ@�P�ϥΡC

- �H�U�𪬹Ϭ��d���ɮת���Ƨ����c

``` Terminal
Demo
�x   demo.mp4                                                  (�d�Ҽv��)
�x   Select.bat                                                (�ؿﾹ ������)
�x
�u�w�w�wbin [�{���ɮ�]
�x   �x   Detector.exe
�x   �x   Selector.exe
�x   �x   *.dll
�x   �x
�x   �|�w�w�wtessdata [��r���Ѽҫ���Ƨ�]
|           *OCR��r���Ѽҫ��ɮ�
�x
�|�w�w�wDatasets [�ͦ��ƾڤθ�Ƨ�]
    |
    �|�w�w�wDataset_XXX [�ͦ��ƾڶ�]
        �x   Detect.bat                                        (����������)
        �x   save_selected_image.png                           (�ؿ粒���s���Ϥ�)
        �x   settings.json                                     (�����{���]�w�ѼơA�ϥΤ��e�ݭק�Ѽ�)
        �x
        �u�w�w�wLabels [���Ҹ�Ƨ�]
        �x       *Labels.png                                   (�Ҧ��������ҹϤ�)
        �x
        �u�w�w�wOutput [���Ѹ�ƿ�X�ɮ�]
        �x   �x   Convert-(Time)-Demo.csv     (�ҪO�ഫ ��X�ɮ�)
        �x   �x   Convert.bat                                   (�ҪO�ഫ ������)
        �x   �x   Template.csv                                  (��X CSV �ҪO)
        �x   �x
        �x   �|�w�w�wDate [������Ƨ�]
        |       (Time) Demo.csv                               (�ھڮɶ���������X CSV �ɮ�)
        �x
        �|�w�w�wVideos [�v����Ƨ�]
                Demo.mp4                                      (demo �v��)
```

- demo.mp4�G�����d�Ҽv���ɮסA�ѨϥΪ̰ѦҡC�i�H�z�L���v���F�ѵ{���B�@�覡�C  
  
- Select.bat�G�ؿﾹ�������ɡA�i�H��ʿ�ܼv�����n���Ѫ��ϰ�A���{���u�B�z���w�ؿ諸�d��(�Ѧ�����)�C
- bin�ؿ��G�{���ɮשҦb��Ƨ��A�]�t�H�U�ɮשM��Ƨ��G
  - Detector.exe�G�����{�����{���ɡA�i�Ψӹ��ܪ��ϰ�i��P�������A�æA�����ɶץXCSV�ɮסC
  - Selector.exe�G�ؿﾹ���{���ɡA�i�ΨӤ�ʿ�ܼv�����n���Ѫ��ϰ�C
  - *.dll�G�{���B��һݪ��ʺA�s���w�ɮסC
  - tessdata�ؿ��G��r���Ѽҫ���Ƨ��A�]�tOCR��r���Ѽҫ��ɮסC
### �H�U�ɮ׬����� "Select.bat" ����۰ʲ���
- Datasets�ؿ��G�ͦ��ƾڤθ�Ƨ��Ҧb��Ƨ��A�]�t�H�U�ɮשM��Ƨ��G  

  - Dataset_XXX�ؿ��G�ھڼv���ͦ����ƾڶ��AXXX ���۰ʽs�� 1 ~ N �C
  - Detect.bat�G�����{���������� (�Ѧ�����)�C
  - save_selected_image.png�G�ؿ粒���s���Ϥ��C
  - settings.json�G�����{���]�w�Ѽ� *(�ϥΤ��e�ݭק�Ѽ�)*�C  
- Labels�ؿ��G�����ɮשҦb��Ƨ��A�]�t�H�U�ɮסG
  - *Labels.png�G�Ҧ��������ҹϤ� *(�ݭn�[�J���ҹϤ�)*�C
- Output�ؿ��G���Ѹ�ƿ�X�ɮשҦb��Ƨ��A�]�t�H�U�ɮשM��Ƨ��G  

  - Template.csv�G�Q�n��X�� CSV �ҪO�˦��C
  - Convert-(Time)-Demo.csv : �ҪO�ഫ�ҿ�X���ɮסC
  - Convert.bat : �ҪO�ഫ�������ɮסC
  - Date�ؿ� ( YYYY-MM-DD )�G�ھڤ����������Ƨ��C  
    - Time ( hh-mm-ss ) Demo.csv�G�ھڮɶ���������X CSV �ɮסC
- Videos�ؿ��G�v���ɮשҦb��Ƨ��A�]�t�H�U�ɮסG  

  - Demo.mp4�Gdemo �v���A�ؿ粒��|�ҳQ�@���즹��Ƨ��A�]�i��J��L�Q�������v���i�h�C

---
## �ϥλ���
### Select.bat
1. ���� `Select.bat` �ɮסC
2. ������|���X��J�����A�N�A�Q�n���Ѫ��v���즲�ܨ䤤�A�i�H�]�w�ĤG�ӰѼ�(���񩵿�h�ֲ@��A�ΨӸ��ǽT����ܧA�n�ؿ���@�ժ��e���A�w�]�Ȭ�����100�@��A����J�ĤG�ӭȪ��ɭԷ|�H����100�@����榹�{��)�C  
   �Ҧp : `Input the Video Path : demo.mp4(�A�����|) 100(����ɶ� �@��)` �A��J������� `Enter` ��}�l�ؿ�{���C  
   
   ![Demo Detector Gif](./readme_src/input_video.gif)  

3. ���ɷ|�i�J����100�@����ܵe�������A�{�����D��|��ܴ��ܦr�� `Pressed "Enter" to choise whitch frame you want to select`�A���� : 
   - ���� `Esc` �� : �h�X�{�� (���������ʧ@)�C
   - ���U `Enter` �� : ��w�A�n���e���C
4. ���ܧ��e�� (���U `Enter` �䤧��)�A���D��|��ܴ��ܦr�� `Pressed any key to continue, or pressed "R" to RE-SELECT frame`�A�X�{�����ܮɥN��A�w�g��w�Q�n���e���A���� : 
   - ���� `Esc` �� : �����h�X���������ʧ@�C
   - ���U `R` �� : ���s��ܷQ�n���e���C
   - ���U��L���� : �~�򱵤U�Ӫ��{���C
   
   ![Demo Detector Gif](./readme_src/choose_video.gif) 

5. ��ܧ��A�Q�ؿ諸�e����K�|�i�J�ؿ�D�{���A���I���ƹ�����ؿ�A�Q�n���Ѫ��ϰ� (�ؿﶶ�ǥ������ӱ����a�����Ǯؿ�A���i�H���ۿ�)�A���� : 
   - ���� `Esc` �� : �h�X�{�� (���������ʧ@)�C
   - �I�� <font color=#green>`��`</font> ��ƹ� : �ؿ�Q�n���d��C
   - ���U `+` �� : �W�[�ؿ�ت��u���ʫסC
   - ���U `-` �� : ��֮ؿ�ت��u���ʫסC 
   - ���U <font color=yellow>`M`</font> �� : �ؿ�������d�� (�u��ؿ�@�ժ����A�B�@�w�n�ؿ�)�C
   - ���U <font color=#FF00FF>`P`</font> �� : �ؿ�S��Ҧ� (MODE) ���ϰ�A�Ψ��˴��O�_�i�J�S�O���Ҧ� (�u��ؿ�@�կS��Ҧ��A�B�@�w�n�ؿ�)�C
   - ���U `Enter` �� : ��w�����ؿ�d��C
   - ���U `S` �� : �x�s���G�õ����ؿ�{���C
   
   ![Demo Detector Gif](./readme_src/select_box.png) 

6. ���U `S` ����N�|�b `Demo` ��Ƨ��U�ͦ� `Datasets` ��Ƨ� (�p�G�w�g�s�b�h���|�ͦ��A�S������Ƨ��~�|�ͦ�)�A�H�� `Dataset_XXX` ���l��Ƨ��A���}�ͦ��� `Dataset_XXX` ��Ƨ��A�o�K�O���{�����A�ͦ����]�w�ɮסA�U���|�b [Detect.bat](#detectbat) ���a�軡���p��]�w�P�ϥΦ��{���A�æ��\�����B��_�ӡC
   
   ![Demo Detector Gif](./readme_src/create_dataset.gif)  

---
### Detect.bat
&emsp;&emsp;�n���\�B�� `Detect.bat` �ݭn�N���Ϥ���J `Labels` ��Ƨ����A�o�ǷӤ��O�n�ΨӻP���ؿ諸�ϰ�i��S�x���A�p�G�ۦ��N�|�P�_���o�@�i�Ӥ��A�ԲӺ�k�i�H�Ѧ� [ORB](https://docs.opencv.org/3.4/d1/d89/tutorial_py_orb.html) ��k�A����k���ثe�}����� (�K�O����) ���ĪG���ΥB�t�׸��֪���סA�B���ݭn�ϥΨ�j�q GPU �B��A�Բӳ]�w�B�J�p�U :  

1. ���} `Labels` ��Ƨ��A�N�^���n���S�x�Ϥ���J����Ƨ��� (�i�H�Ѧ� `Dataset_1/Labels` ��Ƨ�) �A�H�U���X�I��J�����Ϥ��ݭn�S�O�`�N���a�� :
   - �Ϥ��ѪR�פ���ӧC (�i�H�N�v�����}�ҩ�j����ù��b�^���Ϥ��A�ĪG�|���ǽT)�C
   - �S�x�Ϥ����ݭn�Ӧh�I���A�ɶq��n�������Ϥ��d��p�A�u�d�Ϥ�����t�����Y�i�C
   - �N�Ϥ��R�W���̫��X�Q�n���W�� (���ҦW�l������A�̫��X�N�|�s����)�C
   - �S��Ҧ��Цb�A�����W�l�e���[�W `MODE_` �r�ˡA�p `MODE_FreeSpin` �A�o�˵{���N�|�P�_�� MODE �Ҧ��A�᭱�Q�n������W�l���i�H�C
   - �p�G���P�_���X�Ӫ��v���A�i�H��W�^�����i�éR�W�p : `MODE_XXX_FREE` (MODE�Ҧ��R�W�k)�A��L�p�G���K�O���X�Ӫ��i�H�R�W�� `�A�n�����W�l_XXX`�A��X�ɵ{���|�N���u�᭱�ٲ��A�O�d�Ĥ@�Ӧr�� (MODE �Ҧ��h�|�O�d�̫�@��)�C
   
   ![Demo Detector Gif](./readme_src/labels.png)  

2. �]�w `settings.json` �ɮסA���H�U�X�ӰѼ� (�e�ⶵ���ݭn�վ㶵�A��L�i�H����) : 
   - `add_label_seq` : (�����]�w) �C�����a���X�ӡA�p�d�Ҥ����a�������A���p�C�@�����a���T�ӫh�i�H�N���ܬ� : `"add_label_seq" : [3,3,3,3,3]`�A�H�������A�`�N���ﶵ�����P�����ۥ[�`�M�ۦP�C  
   
   - `add_save_addition` : �p�]�w 1 �C�����N��|�h�@�ӧP�_�A�ӳ]�w 2 �C�����N��h�|�h��ӧP�_ (�w�]��2)�C  
   - `continue_detect_frame` : �s��X�չϤ��N��������İ����աC
   - `Continue mode frame` : �s��X�չϤ��N��������ļҦ��աC
   - `Continue money frame` : �s��X�չϤ��N��������Ī����աC
   - `delay_frame` : �v������ (�@��)�A���i�H�]�� 0 �|�d���ʡC
   - `detect_video` : �ҭn�������v���C
   - `detector_threshold` : �����ӷP��(�֭�)�C
   - `mode_labels_box` : �Ҧ������ءC
   - `money_labels_box` : ���������ءC
   - `select_labels_box` : �D�n�����ءC  
  
3. ��H�W���]�w������A���� `Detect.bat` �ɮסA�K�i�H�}�l���ѡA������������X��Ʒ|�x�s�b `Datasets/Dataset_XXX/Output/` ��Ƨ����A�i�H�b��̭��d�ݸԲӸ�� : 
   
   ![Demo Detector Gif](./readme_src/output.gif)  

   �H�W��ƬҬ��@��@�檺�x�s�榡�A�p�G�Q�n��X���A�Q�n���˦��A�h�i�H�ѦҥH�U���� [TransformCSV.bat](#transformcsvbat) ���������ɡC
   
---
### TransformCSV.bat
&emsp;&emsp;��X�ɩ��x�s����Ʀp�U�ϩҥܡA�ѩ��x�s���ɭԨä����D�ϥΪ̩ҷQ�x�s���榡�A�ҥH���O�H�C�դ@�� row ���覡�x�s�A���O�Ҷq��p�e�����W�H�Τ��e���h�i�ܵ��G�A�ҥH�o������{���۰ʤɦ��@�Ӫ�l�ҪO�A�z�L�ק�o�Ӫ�l�ҪO���˦��ӧ令�ۤv�Q�n���˦��C  

![Demo Detector Gif](./readme_src/convert.png)  

�H�U�N���O�����ϥ� `Convert.bat` ���ԲӨB�J : 

1. �i�J `Datasets/Dataset_XXX/Output` ��Ƨ��A�}�� `Template.csv` �ɮסA�}�ҫ�N��קאּ�A�Q�n���˦��A�x�s�������C  

2. �ק粒������ `Convert.bat` �ɮסA�|���X�@�ӹ�ܮءA�N�A�Q�n�ഫ���ɮש즲�ܹ�ܮؤ��åB���U `Enter` �����A�ݨ� " finished! " �r�˥N��ק令�\�C
3. �^�� `Datasets/Dataset_XXX/Output` ��Ƨ��A�i�H�ݨ�s�W�F�@�Ӷ}�Y�� `Convert-` ���ɮסA���ɮ׬��̲ת���X�ɮסA��ھD�@�p�U : 
   
   ![Demo Detector Gif](./readme_src/convert.gif)  

   

---
## �`�N�ƶ�
1. �b���v�ɡA�p�G���T����άO��ܮ� (����i��|�v�T�P�_���G���F��)�A�Ч⥦�����H�K�z�Z�P�_�C
2. �ؿ諸�ɫ�A�аO���d��ɶq���Ͻd��j�@�I�A�W�X�h�S���Y�A���ݭn�ؿ���n�C
3. �P�O�� `Labels` �Ϥ��ѪR�׭n���A�^�����Ӥ��ɶq�p��n�P�_���Ӥ��A�i�H��h�l���O�S�x���I�����h���C