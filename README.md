<img src="https://github.com/Zeqiang-Lai/Mini-DALLE3/assets/26198430/94d7ca03-eded-4fed-93a5-547d869f4717" style="width: 17%" align="right">

<h1 align="center"> Mini DALL•E 3 </h1>

Mini-DALLE3: Interactive Text to Image Generation by Prompting Large Language Models

> An experimental attempt to obtain the interactive and interleave text to image and text to text experience of [DALL•E 3](https://openai.com/dall-e-3) and [ChatGPT](https://openai.com/chatgpt).

https://github.com/Zeqiang-Lai/Mini-DALLE3/assets/26198430/d7af2f0e-2b35-4f64-bace-3113dea4cdfa

## Try yourself

- Download the [checkpoint](https://huggingface.co/h94/IP-Adapter) and save it as following 
```bash
checkpoints
   - models
   - sdxl_models
gradio_app.py
```

- run the following commands, and you will get a gradio-based web demo.

```bash
export OPENAI_API_KEY="your key"
python gradio_app.py
```

## TODO

- [x] Support generating image interleaved in the conversations.
- [ ] Support generating multiple images at once.
- [ ] Support selecting image.


## Citation

If you find this repo helpful, please consider citing us.

```bibtex
@misc{minidalle3,
    author={Zeqiang Lai, Wenhai Wang},
    title={Mini-DALLE3: Interactive Text to Image Generation by Prompting Large Language Models},
    year={2023},
    url={https://github.com/Zeqiang-Lai/Mini-DALLE3},
}
```

## Acknowledgement

[IP-Adapter](https://github.com/tencent-ailab/IP-Adapter) • [Stable Diffusion XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0)

![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FZeqiang-Lai%2FMini-DALLE3&countColor=%23263759&style=flat)
