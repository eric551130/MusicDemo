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

<table>
  <thead>
    <tr>
      <th>Expert</th>
      <th>Baseline</th>
      <th>RL-Trained</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>
          <div>
            <midi-visualizer 
              type="piano-roll" 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/MIDI_1111_song_1_0.88713.mid" 
              id="mainVisualizer">
            </midi-visualizer>
            <midi-player 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/MIDI_1111_song_1_0.88713.mid" 
              sound-font visualizer="#mainVisualizer">
            </midi-player>
          </div>
        </td>
        <td>
          <div>
            <midi-player
              src="https://magenta.github.io/magenta-js/music/demos/melody.mid"
              sound-font visualizer="#myVisualizer">
            </midi-player>
            <midi-visualizer type="piano-roll" id="myVisualizer"></midi-visualizer>
          </div>        
        </td>
        <td>
          <div>
            <midi-player 
              src="https://github.com/eric551130/MusicDemo/blob/main/MIDI_1111/song_5_0.83701.mid" sound-font visualizer="#mainVisualizer3">
            </midi-player>
            <midi-visualizer 
              type="piano-roll" 
              id="mainVisualizer3">
            </midi-visualizer>
          </div>         
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th>Expert</th>
      <th>Baseline</th>
      <th>RL-Trained</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>
          <div>
            <midi-visualizer 
              type="piano-roll" 
              src="https://github.com/eric551130/MusicDemo/blob/main/MIDI_1111/song_5_0.83701.mid"
              id="mainVisualizer4">
            </midi-visualizer>
            <midi-player 
              src="https://github.com/eric551130/MusicDemo/blob/main/MIDI_1111/song_5_0.83701.mid" 
              sound-font visualizer="#mainVisualizer4">
            </midi-player>
          </div>
        </td>
        <td>
          <div>
            <midi-visualizer 
              type="piano-roll" 
              id="mainVisualizer5" 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/song_1_0.88713.mid">
            </midi-visualizer>
            <midi-player 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/song_1_0.88713.mid" sound-font visualizer="#mainVisualizer5">
            </midi-player>
          </div>        
        </td>
        <td>
          <div>
            <midi-visualizer 
              type="piano-roll" 
              id="mainVisualizer6" 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/song_5_0.83701.mid">
            </midi-visualizer>
            <midi-player 
              src="https://github.com/eric551130/MusicDemo/raw/refs/heads/main/MIDI_1111/song_5_0.83701.mid" sound-font visualizer="#mainVisualizer6">
            </midi-player>
          </div>         
        </td>
    </tr>
  </tbody>
</table>

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.4.0"></script>
