# Speech-recognition-for-Polish-language
Purpose of this project is to fit as small as possible model into microcomuputer to make it inference locally.

To find and fix possible issues, program uses python library called ```language_tool_python```

For now there are 2 versions of tunned models.
- whisper-tiny-pl
- whisper-base-pl

You can test models on github spaces:
- https://huggingface.co/spaces/marcsixtysix/whisper-tiny-pl-tunned

Metrics for specified models tested on polish language from common_voice set:
<p align="center">
  <img src="https://github.com/user-attachments/assets/e55fe300-e35e-491a-87f3-a17c56e43b76" />
  <br />
  WER for each model
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e336aa31-4078-425f-8237-8cfc634ff240" />
  <br />
  Inference time plot
</p>
