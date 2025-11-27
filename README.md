# Audio Spectrogram Generator

This notebook demonstrates how to load an audio WAV file, segment it into overlapping windows, apply a Fast Fourier Transform (FFT) to each window, and generate a spectrogram visualization. The spectrogram displays the frequency content of the audio signal over time.

## Key Steps:
- **Load Audio**: Reads a `.wav` file using `wave` and `numpy`.
- **Windowing**: Divides the audio signal into short, overlapping frames.
- **FFT**: Computes the frequency spectrum for each window.
- **Spectrogram**: Visualizes the log-magnitude of the FFT results as a spectrogram.
