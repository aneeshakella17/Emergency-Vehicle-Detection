# Emergency Vehicle Object detection
   >by Aneesh Akella and Andrew Leonard with
   Special Ackwnoledgements to Matterport and Professor Ogunfunmi


 For this project, there are three primary folders:
    -logs
    -mrcnn
    -samples

 Logs contains information needed by Tensorboard to generate useful graphs displaying the variety of loss functions
 Mrcnn contains information about the model itself and its implementation. This is also where the fitting itself occurs.
 Samples contains a folder emergency which contains the code that is used specifically for emergency vehicle detection.
 It contains emergency.py, which adds the classes we would like to detect into the model. It also takes in to user input
 to determine whether we would like to detect instances within pictures or train the model. Also included is emergency_photos.zip,
 the dataset we handmade for this project.


 ## How to Run:
    To train the model:
        python emergency.py --command train --dataset <path to dataset> --weights <path to weights>

    To detect instances within the model:
        python emergency.py --command splash --image <path to image>



