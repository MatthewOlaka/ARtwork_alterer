# ARtwork_alterer

Augmented Reality (AR) project that displays information about an album by replacing the album cover art.

## Getting Started

These instructions will provide an overview of the process of creating the AR-Album-Info application, from creating low-level mockups to final implementation, including the creation of a python script that uses the Spotify API to get information about an album.

### Design and Planning

1. Create low-level mockups of the interface and layout of the application. These mockups should include the basic structure and layout of the application, including the design of the output from the data miner that gets album infomation from the spotify API and makes the images to be overlayed (Shown bellow).

![IMG_0777](https://user-images.githubusercontent.com/72411761/215360841-7a33dafb-8e3e-4610-87b2-574905461637.png)

2. Create high-level mockups of the application. These mockups should include more detailed designs and layout, including the placement of text and images.

![khalid3](https://user-images.githubusercontent.com/72411761/215360898-90d3ba97-5b31-4c4c-87b2-e852802f00ea.png)

3. Define the features and functionality of the application. This includes determining the information that will be displayed when an album cover is scanned and how the user will interact with the application.

4. Plan the creation of a python script that will take an album name and artist as input and use the Spotify API to get information about the album, including the album cover art.

### Development

1. Install and set up Unity and Vuforia on your development machine.

2. Create the basic structure and layout of the application in Unity, including the placement of buttons and other elements.

3. Implement the functionality of the application, including the ability to scan album covers and display information about the album.

4. Create a python script that takes an album name and artist as input and uses the Spotify API to get information about the album, including the album cover art. The script should also generate an image of the album cover art that can be used in the AR application.
(Output from the Data Miner shown below)

![freespirit](https://user-images.githubusercontent.com/72411761/215361051-d61f991d-63ce-4bd9-8fc4-9fe89d7f6f30.png)


5. Test the application on various devices to ensure compatibility and fix any bugs or issues.

6. Integrate Vuforia to enable the recognition of album covers as image targets.

### Deployment

1. Build the final version of the application in Unity.

2. Deploy the application to the appropriate app store or distribution platform.

3. Make the python script available for usage.

### Usage

1. Point the device's camera at an album cover
2. Information about the album will appear on the screen, including the album title, artist, release date, and track list.

### Note

The album cover art must be one of the pre-defined targets in the project in order to display information. If you want to add new album cover you have to run the python script with the desired album and artist name as input to generate a new image target and then add it to the project.

## Built With

- [Unity](https://unity.com/)
- [Vuforia](https://developer.vuforia.com/)
- [Spotify API](https://developer.spotify.com/)
- [Python](https://www.python.org/)

## Author

[Your Name](https://github.com/yourusername)

## License

This project is licensed under the [MIT License](LICENSE).
