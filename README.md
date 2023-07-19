# wavlip_assign
Wav2lip experiment using pretrained model

# Step-1 Segmenting clips where the Person of Interest (POI) is present
Segmented videoclip and audio recording in multiple subclips of exactly same duration where POI was present. 
Task of POI frames was considered as an image classification. Trained a light weight model with 100% accuracy in 10 seconds

# Step-2 Use of pretrained models to fit lip sync on POI
Used Wav2lip model and tweaked the parameters like padding, codeformer quality. 
Also  rescaled the video to a bit lower resolution to reduce artifacts
