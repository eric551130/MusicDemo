<!--
<table>
    <tr>
      <td>1</td>
      <th><audio controls autoplay>
        <source src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/WAV_1111/song_1_0.88713.wav"
        type="audio/mpeg">
       </audio></th>
    </tr>
    <tr>
      <td>2</td>
      <td><audio controls autoplay>
        <source src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/WAV_1111/song_2_0.86003.wav"
        type="audio/mpeg">
       </audio></td>
    </tr>
    <tr>
      <td>3</td>
      <th><audio controls autoplay>
        <source src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/WAV_1111/song_3_0.92767.wav"
        type="audio/mpeg">
       </audio></th>   
    </tr>  
    <tr>
        <td>4</td>
      <td><audio controls autoplay>
        <source src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/WAV_1111/song_4_0.89385.wav"
        type="audio/mpeg">
       </audio></td>
    </tr>
    <tr>
        <td>5</td>
      <td><audio controls autoplay>
        <source src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/WAV_1111/song_5_0.83701.wav"
        type="audio/mpeg">
       </audio></td>
    </tr>
</table>
-->

<div>
<midi-visualizer type="piano-roll" id="mainVisualizer" src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid"></midi-visualizer>
<midi-player src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid" sound-font visualizer="#mainVisualizer" id="mainPlayer">
</midi-player>
</div>

<p>
<label for="midiFile">Load MIDI file:</label>
<input type="file" id="midiFile" name="midiFile" accept="audio/midi, audio/x-midi">
</p>

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.4.0"></script>
