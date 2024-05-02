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
            <li>Make HTML code for Album Art</li>
            <li>Make Deneb Heatmap</li>
            <li>Make Deneb Donut</li>
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
            <li>Clustered Bar Chart: Tracks by No. of Streams</li>
            <li>Custom Visual: Heatmap with Columns(Deneb)</li>
        </ul>
        <h2>Learnt things from this project:</h2>
        <ul>
        </ul>
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
