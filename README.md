# All Things ViTs

Holds code for our CVPR'23 tutorial: [All Things ViTs: Understanding and Interpreting Attention in Vision](https://all-things-vits.github.io/atv). We leverage 🤗 transformers, 🧨 diffusers, timm, and PyTorch for the code samples.

## 🌐 Quick links:

* [Website](https://all-things-vits.github.io/atv) 
* [Virtual website](https://cvpr2023.thecvf.com/virtual/2023/tutorial/18574) on the CVPR portal
* [Interactive demos](https://huggingface.co/all-things-vits) (no setup required)
* Slides (upcoming)
* Video recording (upcoming)

<div align="center">
<img src="https://all-things-vits.github.io/atv/static/figures/teaser.jpg" width=650/>
</div>

## Using the code samples

We provide all the code samples as Colab Notebooks so that no setup is needed locally to execute them.

We divide our tutorial into the following logical sections:

* **`downstream`**: has the notebooks that show how to modify the attention maps for downstream applications.
    * `Attend_and_Excite_explain.ipynb`
    * `Attend_and_Excite_generate_images.ipynb`
* **`explainability`**: has the notebooks that show how to generate explanations from attention-based models (such as Vision Transformers) on the basis of their predictions. 
    * `CLIP_explainability.ipynb`
    * `Comparative_Transformer_explainability.ipynb`
    * `Transformer_explainability.ipynb`
* **`probing`**: has notebooks the probe into the representations learned by the attention-based models (such as Vision Transformers). 
    * `dino_attention_maps.ipynb`
    * `mean_attention_distance.ipynb`

Below we provide links to all the Colab Notebooks:

<table>
  <thead>
    <tr>
      <th><strong>Section</strong></th>
      <th><strong>Notebook Name</strong></th>
      <th><strong>Colab Notebook</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2"><code>downstream</code></td>
      <td><code>Attend_and_Excite_explain.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/downstream/Attend_and_Excite_explain.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
    <tr>
      <td><code>Attend_and_Excite_generate_images.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/downstream/Attend_and_Excite_generate_images.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
    <tr>
      <td rowspan="3"><code>explainability</code></td>
      <td><code>CLIP_explainability.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/explainability/CLIP_explainability.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
    <tr>
      <td><code>Comparative_Transformer_explainability.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/explainability/Comparative_Transformer_explainability.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
    <tr>
      <td><code>Transformer_explainability.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/explainability/Transformer_explainability.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
    <tr>
      <td rowspan="2"><code>probing</code></td>
      <td><code>dino_attention_maps.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/probing/dino_attention_maps.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
      <tr>
      <td><code>mean_attention_distance.ipynb</code></td>
      <td>
        <a href="https://colab.research.google.com/github/all-things-vits/code-samples/blob/main/probing/mean_attention_distance.ipynb">
          <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab">
        </a>
      </td>
    </tr>
  </tr>
  </tbody>
</table>


## Disclaimer

The following notebooks were taken from their original repositories with the authors being aware of this:

* `Attend_and_Excite_explain.ipynb` ([original](https://github.com/yuval-alaluf/Attend-and-Excite/blob/main/notebooks/explain.ipynb))
* `Attend_and_Excite_generate_images.ipynb` ([original](https://github.com/yuval-alaluf/Attend-and-Excite/blob/main/notebooks/generate_images.ipynb))
* `CLIP_explainability.ipynb` ([original](https://github.com/hila-chefer/Transformer-MM-Explainability/blob/main/CLIP_explainability.ipynb))
* `Transformer_explainability.ipynb` ([original](https://github.com/hila-chefer/Transformer-Explainability/blob/main/Transformer_explainability.ipynb))
