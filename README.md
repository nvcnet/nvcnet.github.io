## Abstract

## Code
Will be available soon ...

## Samples

Audio samples are taken from the VCTK data set [1].

### A. Traditional voice conversion
<table style='width: 100%;'>
	<thead>
	  <tr>
	    <th></th>
	    <th>Source</th>
	    <th>Target</th>
	    <th>NVC-Net<sup>&dagger;</sup></th>
	    <th>NVC-Net</th>
	  </tr>
	</thead>

	<tbody>
	  <tr>
	    <th scope="row">M2M</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2M_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2M_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2M_nvcneto.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2M_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>

	<tr>
	    <th scope="row">M2F</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2F_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2F_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2F_nvcneto.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/M2F_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>

	</tbody>
	
	<tr>
	    <th scope="row">F2M</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2M_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2M_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2M_nvcneto.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2M_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>
	
	<tr>
	    <th scope="row">F2F</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2F_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/F2F_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls=""  >
		<source src="resources/audio/F2F_nvcneto.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls=""  >
		<source src="resources/audio/F2F_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>

</table>

**M2M**: Male to male; **M2F**: Male to Female; **F2M**: Female to male; **F2F**: Female to female 


### B. Zero-shot voice conversion


<table style='width: 100%;'>
	<thead>
	  <tr>
	    <th></th>
	    <th>Source</th>
	    <th>Target</th>
	    <th>NVC-Net</th>
	  </tr>
	</thead>

	<tbody>
	  <tr>
	    <th scope="row">S2U</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/S2U_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/S2U_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/S2U_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>

	<tr>
	    <th scope="row">U2S</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2S_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2S_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2S_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>

	</tbody>
	
	<tr>
	    <th scope="row">U2U</th>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2U_source.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2U_target.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	    <td>
	      <audio controls="" >
		<source src="resources/audio/U2U_nvcnet.wav" type="audio/wav">
		Your browser does not support the audio element.
	      </audio>
	    </td>
	  </tr>
</table>

**S2U**: Seen to unseen; **U2S**: Unseen to seen; **U2U**: Unseen to seen 


### C. Diversity

Source
<audio controls="" >
 <source src="resources/audio/U2U_target.wav" type="audio/wav">
		Your browser does not support the audio element.
</audio>

Target
<audio controls="" >
 <source src="resources/audio/U2U_target.wav" type="audio/wav">
		Your browser does not support the audio element.
</audio>

Samples produced by NVC-Net
<audio controls="" >
 <source src="resources/audio/U2U_target.wav" type="audio/wav">
		Your browser does not support the audio element.
</audio>

#### References
[1] [C. Veaux, J. Yamagishi, and K. MacDonald. Superseded - cstr vctk corpus: English multi-speaker corpus
for cstr voice cloning toolkit, 2017.](http://datashare.is.ed.ac.uk/handle/10283/2651)

