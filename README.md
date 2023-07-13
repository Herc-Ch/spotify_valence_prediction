# spotify_valence_prediction
Predicting the valence (happiness) of spotify tracks via non-nn and nn techniques

Spotify uses the metric of "valence" to determine how happy or cheerful a piece of music sounds. This metric was not developed by Spotify itself but was initially developed by Echo Nest, a company that was acquired by Spotify in 2014. The exact calculation method for valence of each track is not known. Some details can be found in a blog post, which you can access here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

Your goal is to find a way to calculate the valence of a music track. To achieve this, you'll need to utilize the Spotify API (Spotify's programming interface) by following the instructions provided here: https://developer.spotify.com/. You can use the following two API calls to gather the data that you will process:

Get Track's Audio Features
Get Tracks' Audio Features
Optionally, you can also use the "Get Track's Audio Analysis" call.

As a starting point, you can use the data for tracks that have appeared on the top listening charts in various countries, which you can find here: https://doi.org/10.5281/zenodo.4778562 in the file charts.zip.

## Task 1: Valence Prediction without Neural Networks
Utilize Machine Learning techniques of your choice, excluding neural networks, to predict the valence of songs in the best possible way.

You should employ at least three different methods. For each method, search for the best model with the optimal hyperparameter values.

Once you have found the best model, explain, to the best of your ability, which features influence the valence of a song.

After finding the best model, you will use it to calculate the valence of the songs provided in the file spotify_ids.txt. The metric to be used should be Mean Absolute Error (MAE).

## Task 2: Valence Prediction with Neural Networks
Now, you will attempt to create the best model using neural networks.

You are free to use any neural network architecture you prefer. Be mindful of overfitting.

Once you have found the best model, you will use it to calculate the valence of the songs provided in the file spotify_ids.txt. The metric to be used should be Mean Absolute Error (MAE).

In the end, which approach yielded the best results, with or without neural networks?
