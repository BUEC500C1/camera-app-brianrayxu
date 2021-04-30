# camera-app-brianrayxu
camera-app-brianrayxu created by GitHub Classroom

## Overview
The purpose of this application is to scan product barcodes and help the user remember where they found them on the map. In addition, the privacy of the user and any of the people included in the picture will be protected.

## MVP + User Stories
### MVP
- Camera module with capability to saves images and detect faces and barcodes.
- Map module capable of showing Geo-tags of saved barcodes/products
- Mobile + WEB application interfaces

### User Stories
- As a user, I want to be able to scan barcodes and save the location of where the photo was taken.
- As a user, I want to have my privacy and identity protected. This includes picture metadata such as location and the faces of others in the images taken to be obfuscated. 
- As a user, I want to be able to edit my saved barcodes. This means I can rate, delete, favorite my saved barcodes.
 
## Design

### Camera Screen
The camera screen is designed such that the user can scan a barcode and save that data
<img src="Images/openvidulogo.png" alt="Openvidu" height="150" width="750"/>
### Map Screen
The map screen is designed so that the user can view their past saved QRcode locations. On picture taken, a tracker entry is made in our database so the user can load all their entries.
<img src="Images/openvidulogo.png" alt="Openvidu" height="150" width="750"/>
### Backend/ Persistance
The backend used for this application is Firebase. I use the react native package "react-native-firebase" in order to interface react native with Firebase.

## References
