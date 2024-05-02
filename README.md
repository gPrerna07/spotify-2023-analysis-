<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <header>
        <h1>Most Streamed Spotify Songs 2023</h1>
    </header>
     <main>
        <h2>Task List:</h2>
        <ol>
            <li>Download dataset</li>
            <li>Enrich Dataset with GenAI/Python</li>
            <li>Make Glass morphism Background</li>
            <li>Load into PowerBI</li>
            <li>Create DAX</li>
            <li>Make horizonatal bar graph</li>
            <li>create line graph</li>
            <li>create table </li>
        </ol>
        <h2>About the dataset:</h2>
        <p>The dataset consists of the following features:</p>
        <table>
            <tr>
                <th>Feature</th>
                <th>Description</th>
            </tr>
            <tr>
                <td>track_name</td>
                <td>Name of the song</td>
            </tr>
            <tr>
                <td>Artist(s)_name</td>
                <td>name of the artist</td>
           </tr>
            <tr>
                <td>artist_count</td>
                <td>number of the artists contributing to the song </td>
            </tr>
            <tr>
                <td>release year</td>
                <td>year when the song was released</td>
            </tr>
            <tr>
                <td>released_month</td>
                <td>Month when the song was released</td>
            </tr>
            <tr>
                <td>released_day</td>
                <td>Day of the month when the song was released</td>    
            </tr>
            <tr>
                <td>in_spotify_playlists</td>
                <td>Number of Spotify playlists the song is included in</td>
            </tr>
            <tr>
                <td>in_spotify_charts</td>
                <td> Presence and rank of the song on Spotify charts</td>
            </tr>
            <tr>
                <td>streams</td>
                <td>Total number of streams on Spotify</td>
            </tr>
            <tr>
                <td>in_apple_playlists</td>
                <td>  Number of Apple Music playlists the song is included in</td>
            </tr>
            <tr>
            <td>in_apple_charts</td>
            <td></td>Presence and rank of the song on Apple Music charts</td>   
            </tr>
            <tr>
                <td>in_deezer_playlists</td>
                <td>Number of Deezer playlists the song is included in</td>
            </tr>
            <tr>
                <td>in_deezer_charts</td>
                <td> and rank of the song on Deezer charts</td>
            </tr>
            <tr>
                <td>in_shazam_charts</td>
                <td>Presence and rank of the song on Shazam charts</td>
            </tr>
            <tr>
                <td>bpm</td>
               <td>Beats per minute, a measure of song tempo</td>
            </tr>
            <tr>
                <td>key</td>
                <td>Key of the song</td>
            </tr>
            <tr>
                <td>mode</td>
                <td>Mode of the song (major or minor)</td>
            </tr>
            <tr>
                <td>danceability_%</td>
                <td>Percentage indicating how suitable the song is for dancing</td>
            </tr>
            <tr>
                <td>valence_%</td>
                <td>Positivity of the song's musical content</td>
            </tr>
            <tr>
                <td>energy_%</td>
                 <td>Perceived energy level of the song</td>
            </tr>
            <tr>
                <td>acousticness_%</td>
                <td>Amount of acoustic sound in the song</td>
            </tr>
            <tr>
                <td>instrumentalness_%</td>
                <td>Amount of instrumental content in the song</td>
            </tr>
            <tr>
                <td>liveness_%</td>
                <td>Presence of live performance elements</td>
            </tr>
            <tr>
                <td>speechiness_%</td>
                 <td>Amount of spoken words in the song</td>
            </tr>
        </table>
        <p>Link for the Dataset <a href="https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023?rvi=1">Click Here!</a>. The dataset is from Kaggle.</p>
         <h2>Visual Used:</h2>
        <ul>
            <li>Slicers: Date, Track, Artist, Year.</li>
            <li>Card: Average streams per Year, Top Song vs AVG</li>
            <li>Card(New): Track, Artist, Release Date, Streams, No. of artists</li>
            <li>Horizonatal Bar Chart: Tracks by No. of Streams</li>
            <li>line graph:stream over time</li>
        </ul>
        <h2>Learnt things from this project:</h2>
         <ul>
             <ol>
            <li>Line Graph (Streams by Release Date): This chart shows the trend of streams over time, with the x-axis representing the release date of tracks and the y-axis representing the number of streams. It's useful for visualizing changes and trends over a period.</li>
         <li>Table (Tracks and Streams By Month): This is not a chart but a table that lists the number of tracks and average streams for each month. Tables are great for presenting exact figures and allowing for quick comparisons between different categories..</li>
         <li>Bar Graph (Daily Stream For All Tracks): This chart uses horizontal bars to represent the number of streams for each day of the week. The length of each bar corresponds to the total streams, making it easy to compare streaming activity across different days.</li>
         <li>Daily Streaming Patterns: The bar graph "Daily Stream For All Tracks" indicates that Friday has the highest number of streams, followed by Thursday and Wednesday. This suggests that streaming activity may be higher towards the end of the workweek.</li>
         <li>Album Covers (Top 5 Most Streamed Tracks): While not a chart, this visual representation shows the album covers of the top 5 most streamed tracks, providing a quick visual reference for recognizing popular songs.
              </li>
        </ul>
             </ol>
        <h2>Some Important Insights from the Dashboard:</h2>
        <ul>
            <li>The track with the most number of streams was Blinding Lights, followed by Shape of You and Someone You Loved.</li>
            <li>The lowest streamed song was Que Vuelvas.</li>
            <li>The number of songs per year increased drastically after 2011.</li>
            <li>The month with the highest number of tracks was Jan.</li>
            <li>The week with the highest number of tracks was Fri.</li>
        </ul>
    </main>
</body>
</html>
