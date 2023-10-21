<style type="text/css">
  .tg {
    border-collapse: collapse;
    border-color: #9ABAD9;
    border-spacing: 0;
  }

  .tg td {
    background-color: #EBF5FF;
    border-color: #9ABAD9;
    border-style: solid;
    border-width: 1px;
    color: #444;
    font-family: Arial, sans-serif;
    font-size: 14px;
    overflow: hidden;
    padding: 0px 20px;
    word-break: normal;
    font-weight: bold;
    vertical-align: middle;
    horizontal-align: center;
    white-space: nowrap;
  }

  .tg th {
    background-color: #409cff;
    border-color: #9ABAD9;
    border-style: solid;
    border-width: 1px;
    color: #fff;
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: normal;
    overflow: hidden;
    padding: 0px 20px;
    word-break: normal;
    font-weight: bold;
    vertical-align: middle;
    horizontal-align: center;
    white-space: nowrap;
    padding: 10px;
    margin: auto;
  }

  .tg .tg-0pky {
    border-color: inherit;
    text-align: center;
    vertical-align: top,
  }

  .tg .tg-fymr {
    border-color: inherit;
    font-weight: bold;
    text-align: center;
    vertical-align: top
  }
  .slider {
  -webkit-appearance: none;
  width: 75%;
  height: 15px;
  border-radius: 5px;
  background: #d3d3d3;
  outline: none;
  opacity: 0.7;
  -webkit-transition: .2s;
  transition: opacity .2s;
}

.slider::-webkit-slider-thumb {
  -webkit-appearance: none;
  appearance: none;
  width: 25px;
  height: 25px;
  border-radius: 50%;
  background: #409cff;
  cursor: pointer;
}

.slider::-moz-range-thumb {
  width: 25px;
  height: 25px;
  border-radius: 50%;
  background: #409cff;
  cursor: pointer;
}
audio {
    width: 250px;
}
</style>

## Abstract 
Recent work in spontaneous text-to-speech (TTS) has achieved naturalistic synthesis of creaky voice, a voice quality that has many pragmatic as well as paralinguistic functions. In this paper, we investigate the perception of two types of synthesized creaky voice by non-expert listeners. We annotated a spontaneous speech corpus using an automatic creaky phonation detection tool, and a Tacotron 2 TTS engine that was modified with a creaky phonation embedding with which we are capable of synthesizing a creaky voice style. We performed two subjective listening experiments in which the participants rated non-positional creak as sounding less certain, less positive, and more turn final, while positional creak at the end of an utterance was rated as more turn final than the stimuli synthesized with modal phonation. We also performed an objective analysis of the two types of creaky and modal phonation using a creak detection tool, which indicated significant differences in the level of creaky phonation present for each phonation type.

# Stimuli for the Subjective Listening Experiments
<table class="tg">
  <thead>
    <tr>
      <th class="tg-0pky">Stimulus</th>
      <th class="tg-0pky">No creak</th>
      <th class="tg-0pky">Non-terminal creak</th>
      <th class="tg-0pky">No creak</th>
      <th class="tg-0pky">Terminal creak</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td class="tg-0pky">
            1
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_2_no_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_2_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_2_no_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
         <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_2_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
    </tr>
    <tr>
        <td class="tg-0pky">
            2
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_3_no_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_3_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_3_no_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_3_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
    </tr>
    <tr>
        <td class="tg-0pky">
            3
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_4_no_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_4_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_4_no_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_4_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
    </tr>
    <tr>
        <td class="tg-0pky">
            4
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_5_no_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_5_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_5_no_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_5_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
    </tr>
    <tr>
        <td class="tg-0pky">
            5
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_no_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_6_creak_full.wav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_6_no_creak_finalwav" type="audio/wav" />
          </audio>
        </td>
        <td class="tg-0pky">
          <audio id="audio-small" controls>
            <source src="./audio/dialogue_6_creak_final.wav" type="audio/wav" />
          </audio>
        </td>
    </tr>
</table>