# Extract and save feature

Run `save_feature.py`.

- Each subfolder in the `tran_set\` has an `.ods` file stating the list of songs, and `.mp3` files for songs.
    - `Progressive_Rock_Songs\`: {'songs': 142, 'others': ['prog_train.ods']}
    - `Not_Progressive_Rock\Top_Of_The_Pops\`: {'songs': 87, 'others': ['notprog_top_pops_train.ods']}
    - `Not_Progressive_Rock\Other_Songs\`: {'songs': 272, 'others': ['notprog_other_train.ods']}

- Load music files using `librosa`.
    - It has [features](https://librosa.org/doc/latest/feature.html) of 
        - Spectral
            - Chromagram
            - Mel-scaled spectrogram
            - Mel-frequency cepstral coefficients (MFCCs)
        - Rythym
            - Tempo
        - Others




# Run algorithm

Run `main.py`.