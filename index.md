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

<!-- <audio controls autoplay>
        <source src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/WAV_1111/song_5_0.83701.wav"
        type="audio/mpeg">
       </audio></th> -->

<div>
  <midi-visualizer type="piano-roll" id="mainVisualizer, #mainVisualizer1" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
  <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer, #mainVisualizer1" id="mainPlayer">
  </midi-player>
</div>


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
        <th>
          <div>
            <midi-visualizer type="piano-roll" id="mainVisualizer" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer" id="mainPlayer">
            </midi-player>
          </div>
        </th>
        <th>
          <div>
            <midi-visualizer type="piano-roll" id="mainVisualizer" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer" id="mainPlayer">
            </midi-player>
          </div>       
        </th>
        <th>
          <div>
            <midi-visualizer type="piano-roll" id="mainVisualizer" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer" id="mainPlayer">
            </midi-player>
          </div>       
        </th>
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
            <midi-visualizer type="piano-roll" id="mainVisualizer4" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer4" id="mainPlayer">
            </midi-player>
          </div>
        </td>
        <td>
          <div>
            <midi-visualizer type="piano-roll" id="mainVisualizer5" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer5" id="mainPlayer">
            </midi-player>
          </div>       
        </td>
        <td>
          <div>
            <midi-visualizer type="piano-roll" id="mainVisualizer6" src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid"></midi-visualizer>
            <midi-player src="https://raw.githubusercontent.com/eric551130/MusicDemo/main/MIDI_1111/expert_009.mid" sound-font visualizer="#mainVisualizer6" id="mainPlayer">
            </midi-player>
          </div>       
        </td>
    </tr>
  </tbody>
</table>

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.4.0"></script>
