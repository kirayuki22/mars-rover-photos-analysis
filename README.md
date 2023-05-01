# mars-rover-photos-analysis

Mars Rover Photos Analysis

This project displays two interactive charts related to Mars rover photos. The first chart shows the number of photos taken over time, and the second chart compares the total number of photos taken by each rover. The purpose of this project is to visualize the progress of Mars exploration and provide insights into the photo-taking capabilities and priorities of various rover missions.

## APIs used

1. **NASA Open APIs**: NASA's APIs provide access to various data related to astronomy, space exploration, and earth science. We used the Mars Rover Photos API to fetch the data for our charts. The API was chosen because it offers relevant data for our project's purpose and demonstrates the increasing capabilities of Mars rovers over time.

   - Documentation: https://api.nasa.gov/
   - Mars Rover Photos API URL: https://api.nasa.gov/mars-photos/api/v1/rovers?api_key=YOUR_API_KEY

## How the APIs were used

We used the Mars Rover Photos API to fetch data about each rover, including the total number of photos taken and the rover's launch date. The data was then processed and visualized in two charts:

1. **Mars Rover Photos Over Time (Line Chart)**: The x-axis represents the years, and the y-axis represents the total number of photos taken. This chart shows how the frequency of photo-taking has changed over time.

2. **Comparison of Mars Rovers by Photos Taken (Bar Chart)**: This chart compares the total number of photos taken by each Mars rover, highlighting the differences in their photo-taking capabilities and mission durations.
