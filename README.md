# NMR Sonification: *Signals in the Static*

**Can a protein's chemical shifts become an alt-indie rock track?** This project turns paired backbone amide \(^{1}\mathrm{H}\) and \(^{15}\mathrm{N}\) chemical-shift values into an original instrumental composition.

🎧 **Listen to the track:** [Signals in the Static — MP3](./Signals_in_the_Static_NMR_music.mp3)

## The idea

Built for **BT4408 Structural Biology — Assignment 2**, this piece uses the supplied `6457_simulated_hsqc_backbone.csv` dataset: 72 paired backbone-amide entries associated with human ubiquitin (BMRB entry 6457).

Instead of treating the values as ordinary numbers, the project maps them into a musical pitch sequence:

1. Convert each chemical shift into a frequency offset using the relevant spectrometer frequency.
2. Map the offsets to the nearest note in 12-tone equal temperament, then octave-fold the notes into playable registers.
3. Follow residue order to create the lead-guitar melody from the **¹H** sequence and a lower bass counterline from the **¹⁵N** sequence.
4. Arrange those lines into a Western alt-indie rock track, adding guitars, bass, drums, a soft pad, and a D-minor-centred chord progression.

## Track notes

- **Style:** Instrumental Western alt-indie rock
- **Duration:** Approximately 1 min 48 sec
- **Tempo:** 110 BPM, 4/4 time
- **Musical structure:** Verse/chorus-style arrangement with recurring hooks

The mapping is a creative sonification method, not a biological prediction. The chord progression, rhythm, sound design, and repeated hooks are compositional choices. The input CSV is labelled *simulated*, so its values are used as supplied rather than presented as independently verified experimental peaks.

## Reference

- **Biological Magnetic Resonance Data Bank (BMRB), entry 6457 — Human ubiquitin:** [bmrb.io/data_library/summary/?bmrbId=6457](https://bmrb.io/data_library/summary/?bmrbId=6457)

---

*Signals in the Static* is a small experiment at the intersection of structural biology, data sonification, and music: a way to listen to a dataset, while remembering that the melody is an artistic mapping rather than the protein “singing” literally.
