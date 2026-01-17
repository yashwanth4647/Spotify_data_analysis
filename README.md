# Spotify_data_analysis

**Problem Statement**
Spotify manages a vast ecosystem of over 586,000 tracks and 1.1 million artists. As a data analyst, the task is to perform an EDA to identify the defining characteristics of music across different eras (from 1922 to 2021). The goal is to uncover hidden patterns in audio features—such as loudness, energy, and acousticness—and determine how these variables correlate with a song's popularity to understand what drives global music trends.

**Overall Insights**
**1. The Drivers of Popularity**
High Energy & Loudness: There is a strong positive correlation (0.78) between Energy and Loudness. The data suggests that popular modern tracks tend to be higher in energy and recorded at higher volumes.

The Decline of Acousticness: Popularity is negatively correlated with Acousticness (-0.37). This indicates that traditional acoustic tracks are generally less likely to reach "hit" status compared to electronic or highly produced tracks.

Top Performers: At the time of this data collection, the most popular tracks (scoring 94–100) were dominated by artists like Justin Bieber (Peaches), Olivia Rodrigo (drivers license), and The Weeknd (Save Your Tears).

**2. Evolution of Music Trends (1922–2021)**
Shift in Duration: The analysis involves tracking song lengths over a century. By converting milliseconds to seconds, the study provides a clearer view of how song durations have evolved to meet the needs of radio and digital streaming.

Sonic Progress: Over time, music has moved away from high acousticness toward more energetic and "loud" sonic profiles, as seen in the correlation matrices and time-series data.

**3. Audio Feature Relationships**
Inverse Relationships: Acousticness has a significant negative correlation with Energy (-0.73) and Loudness (-0.59). This confirms a clear technical divide between acoustic music and high-production energy tracks.

Danceability & Valence: There is a positive relationship between Danceability and Valence (musical positiveness), suggesting that songs intended for dancing often carry a more joyful or positive emotional tone.

**4. Data Quality & Distribution**
Popularity Skew: The average popularity score across the entire dataset is relatively low (~27.5), as a massive volume of tracks (often older recordings or niche content) have a popularity score of 0.

Cleaned Metadata: The analysis required significant pre-processing, including handling missing song names and artist follower counts to ensure the statistical results remained accurate.
