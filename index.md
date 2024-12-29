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
  <tr>
      <td>
        <div>
          <midi-visualizer 
            type="piano-roll" 
            id="mainVisualizer">
          </midi-visualizer>
          <midi-player 
            src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid" 
            sound-font visualizer="#mainVisualizer">
          </midi-player>
        </div>
      </td>
      <td>
        <div>
          <midi-visualizer type="piano-roll" id="mainVisualizer2" src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid"></midi-visualizer>
          <midi-player src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid" sound-font visualizer="#mainVisualizer2" id="mainPlayer">
          </midi-player>
        </div>        
      </td>
      <td>
        <div>
          <midi-player
            src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid"
            sound-font visualizer="#section3 midi-visualizer">
          </midi-player>
          <midi-visualizer
            src="https://cdn.jsdelivr.net/gh/cifkao/html-midi-player@2b12128/jazz.mid">
          </midi-visualizer>
        </div>        
      </td>
  </tr>


</table>

<script src="https://cdn.jsdelivr.net/combine/npm/tone@14.7.58,npm/@magenta/music@1.23.1/es6/core.js,npm/focus-visible@5,npm/html-midi-player@1.4.0"></script>
