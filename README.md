
# 🌋 LLaVA-Interactive

*An All-in-One Demo for Image Chat, Segmentation and Generation/Editing.*

[[Project Page](https://llava-vl.github.io/llava-interactive/)] [[Demo](https://llavainteractive.ngrok.io/)] [[Paper](https://arxiv.org/abs/2311.00571)]

<p align="center">
    <img src="https://github.com/LLaVA-VL/llava-interactive/blob/main/images/llava_interactive_logo.png" width="45%"> 
    <br>
</p>

# Install

Installing this project requires CUDA 11.7 or above. Follow the steps below: 

```bash
git clone https://github.com/LLaVA-VL/LLaVA-Interactive-Demo.git
conda create -n llava_int -c conda-forge -c pytorch python=3.10.8 pytorch=2.0.1 -y
conda activate llava_int
cd LLaVA-Interactive-Demo
pip install -r requirements.txt
source setup.sh
```

# Run the demo

To run the demo, simply run the shell script. 

```bash
./run_demo.sh
```

<p align="center">
    <img src="https://github.com/LLaVA-VL/llava-interactive/blob/main/images/llava_interactive_workflow.png" width="50%"> 
    <br>
</p>


# Citation

If you find LLaVA-Interactive useful for your research and applications, please cite using this BibTeX:
```bash
  @article{chen2023llava_interactive,
    author      = {Chen, Wei-Ge and Spiridonova, Irina and Yang, Jianwei and Gao, Jianfeng and Li, Chunyuan},
    title       = {LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing},
    publisher   = {arXiv:2311.00571},
    year        = {2023}
  }
```
  
# Related Projects

- [LLaVA: Large Language and Vision Assistant](https://github.com/haotian-liu/LLaVA)
- [SEEM: Segment Everything Everywhere All at Once](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)
- [GLIGEN: Open-Set Grounded Text-to-Image Generation](https://github.com/gligen/GLIGEN)

# Acknowledgement

- [LaMa](https://github.com/advimman/lama): A nice tool we use to fill the background holes in images.

# Terms of use
By using this service, users are required to agree to the following terms: The service is a research preview intended for non-commercial use only. It only provides limited safety measures and may generate offensive content. It must not be used for any illegal, harmful, violent, racist, or sexual purposes. The service may collect user dialogue data for future research. For an optimal experience, please use desktop computers for this demo, as mobile devices may compromise its quality.
 
# License
The service is a research preview intended for non-commercial use only, subject to the model [License](https://github.com/facebookresearch/llama/blob/main/MODEL_CARD.md) of LLaMA, [Terms of Use](https://openai.com/policies/terms-of-use) of the data generated by OpenAI, and [Privacy Practices](https://chrome.google.com/webstore/detail/sharegpt-share-your-chatg/daiacboceoaocpibfodeljbdfacokfjb) of ShareGPT. Please contact us if you find any potential violation.
