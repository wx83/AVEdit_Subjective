# Introduction
In this study, we are interested in evaluating both our synthetic dataset generation pipeline and the SAVE editor for removing objects from audio and video. You will be shown a series of sounding videos and asked to rate them based on how well the specified target object has been removed. We leave target object name on the top. 

Link to the survey:
<a href="https://docs.google.com/forms/d/e/1FAIpQLSe3W79IJcW1e_yBV-7RYQalWXhzs2Kgds1rhy3g0HiZp0f7hA/viewform?usp=publish-editor" target="_blank">Click here to open the survey</a>

**Please select Version A at the top. Thanks!**

# Section 1:
<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 1 Target<br/>Object: guitar</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 2 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 2 Target<br/>Object: speaker</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-65Ee58UCQw/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-65Ee58UCQw/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-bfIrdu5yEo/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-bfIrdu5yEo/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 3 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 3 Target<br/>Object: man</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 4 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 4 Target<br/>Object: two-stroke engine</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-gNn39_SfMM/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-gNn39_SfMM/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_balanced_train_5gO1h5yQUpQ_30.000/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_balanced_train_5gO1h5yQUpQ_30.000/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 5 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 5 Target<br/>Object: engine</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 6 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 6 Target<br/>Object: computer keyboard</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_ukXFtz6kgI4_30.000/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_ukXFtz6kgI4_30.000/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_PZACLpEasFU_30.000/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_PZACLpEasFU_30.000/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>

# Section 2:
<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 1 Target<br/>Object: violin</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 2 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 2 Target<br/>Object: machine</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-il1SY0ZSi8/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-il1SY0ZSi8/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-a4Z0Xi4K18/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-a4Z0Xi4K18/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 3 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 3 Target<br/>Object: cat</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 4 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 4 Target<br/>Object: human</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-f3amaXRaHs/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/-f3amaXRaHs/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval__Uf47SnKl5Q_30.000/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval__Uf47SnKl5Q_30.000/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 5 Source</strong></td>
    <td style="text-align: center; border-right: 3px solid #ccc; padding-right: 15px;"><strong>Sample 5 Target<br/>Object: hairdryer</strong></td>
    <td style="text-align: center; padding-left: 15px;"><strong>Sample 6 Source</strong></td>
    <td style="text-align: center;"><strong>Sample 6 Target<br/>Object: motorcycle</strong></td>
  </tr>
  <tr>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_-qfsR2ZEUcw_30.000/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="border-right: 3px solid #ccc; padding-right: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/audioset_eval_-qfsR2ZEUcw_30.000/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="padding-left: 15px;">
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/kling_nonmotorizedlandvehicle_10921/video_audio_src.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="240" height="180" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/dataset_pair/kling_nonmotorizedlandvehicle_10921/video_audio_target.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>

# Section 3:

<div style="text-align: center; margin-bottom: 30px;">
  <video width="320" height="240" controls>
    <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/save/video_audio_src.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

**Target Object is**

<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1: Target Object: fire truck </strong></td>
    <td style="text-align: center;"><strong>Sample 2: Target Object: fire truck </strong></td>
    <td style="text-align: center;"><strong>Sample 3: Target Object: fire truck </strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/lgvi_audit/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/lgvi_zeus/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/vace_zeus/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 4: Target Object: fire truck </strong></td>
    <td style="text-align: center;"><strong>Sample 5: Target Object: fire truck </strong></td>
    <td style="text-align: center;"><strong>Sample 6: Target Object: fire truck </strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/mcfm/audioset_balanced_train_-z47zN0YyE4_420.000/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/save/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/videoinpainter_zeus/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 7: Target Object: fire truck </strong></td>
    <td style="text-align: center;"><strong>Sample 8: Target Object: fire truck</strong></td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/vace_audit/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_balanced_train_-z47zN0YyE4_420.000/videoinpainter_audit/audioset_balanced_train_-z47zN0YyE4_420.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>

# Section 4:

<div style="text-align: center; margin-bottom: 30px;">
  <video width="320" height="240" controls>
    <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/save/video_audio_src.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1: Target Object: man </strong></td>
    <td style="text-align: center;"><strong>Sample 2: Target Object: man</strong></td>
    <td style="text-align: center;"><strong>Sample 3: Target Object: man</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/lgvi_audit/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/lgvi_zeus/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/mcfm/audioset_eval_aXV-yaFmQNk_70.000/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 4: Target Object: man </strong></td>
    <td style="text-align: center;"><strong>Sample 5: Target Object: man</strong></td>
    <td style="text-align: center;"><strong>Sample 6: Target Object: man</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/save/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/vace_audit/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/vace_zeus/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 7: Target Object: man </strong></td>
    <td style="text-align: center;"><strong>Sample 8: Target Object: man</strong></td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/videoinpainter_audit/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/audioset_eval_aXV-yaFmQNk_70.000/videoinpainter_zeus/audioset_eval_aXV-yaFmQNk_70.000_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>


# Section 5:

<div style="text-align: center; margin-bottom: 30px;">
  <video width="320" height="240" controls>
    <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/save/video_audio_src.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1: Target Object: fireworks </strong></td>
    <td style="text-align: center;"><strong>Sample 2: Target Object: fireworks </strong></td>
    <td style="text-align: center;"><strong>Sample 3: Target Object: fireworks</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/lgvi_audit/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/lgvi_zeus/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/mcfm/kling_explosion_2210/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 4: Target Object: fireworks</strong></td>
    <td style="text-align: center;"><strong>Sample 5: Target Object: fireworks</strong></td>
    <td style="text-align: center;"><strong>Sample 6: Target Object: fireworks</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/save/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/vace_audit/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/vace_zeus/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 7: Target Object: fireworks</strong></td>
    <td style="text-align: center;"><strong>Sample 8: Target Object: fireworks</strong></td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/videoinpainter_audit/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_explosion_2210/videoinpainter_zeus/kling_explosion_2210_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>


# Section 6:

<div style="text-align: center; margin-bottom: 30px;">
  <video width="320" height="240" controls>
    <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/save/video_audio_src.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<table>
  <tr>
    <td style="text-align: center;"><strong>Sample 1: Target Object: motorcycle</strong></td>
    <td style="text-align: center;"><strong>Sample 2: Target Object: motorcycle</strong></td>
    <td style="text-align: center;"><strong>Sample 3: Target Object: motorcycle</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/lgvi_audit/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/lgvi_zeus/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/mcfm/kling_motorvehicleroad_20512/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 4: Target Object: motorcycle</strong></td>
    <td style="text-align: center;"><strong>Sample 5: Target Object: motorcycle</strong></td>
    <td style="text-align: center;"><strong>Sample 6: Target Object: motorcycle</strong></td>
  </tr>
  <tr>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/save/video_audio_generated.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/vace_audit/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td>
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/vace_zeus/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
  <tr>
    <td style="text-align: center;"><strong>Sample 7: Target Object: motorcycle</strong></td>
    <td style="text-align: center;"><strong>Sample 8: Target Object: motorcycle</strong></td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/videoinpainter_audit/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
    <td style="text-align: center;">
      <video width="320" height="240" controls>
        <source src="https://wx83.github.io/AVEdit_Subjective/versionA/edit_result/kling_motorvehicleroad_20512/videoinpainter_zeus/kling_motorvehicleroad_20512_combined.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </td>
  </tr>
</table>