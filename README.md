This is a custom neural net trained detection model using YOLOv3.  It is used to detect swastikas within images.  The original intention was to scan profile photos uploaded to Twitch so the users could be preemptively banned.  But it could be used for any other similar type of scans.

The model needs some work, as the dataset used to train was limited (~400 images, batch size of 8).  I plan to improve this soon, but it can be used to reliably detect clear images.  Lower resolution images are hit and miss currently.
