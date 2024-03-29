# Scene Text Detection for Driving Videos

<p align="center">
<b>Abstract</b>
<br>
With the current trend of automation gradually dominating many aspects of human life, the demand for highly accurate and timely responsive automated systems has become essential. Specifically, in the context of transportation, self-driving vehicles, automated traffic monitoring and analysis systems require a capability to read and comprehend the traffic context at a given moment to make informed decisions. My research, "Scene Text Detection for Driving Videos", aims at supporting automated transportation systems in capturing textual information from traffic signs.
</p>

## System Pipeline

![Scene Text Detection for Driving Videos System pipeline](images/system/pipeline.svg "Scene Text Detection for Driving Videos System pipeline")

### Module 1: Detect and classify traffic signs

- Model: [**PP-YOLOE+**](https://arxiv.org/abs/2203.16250) from [Paddle Detection](https://github.com/PaddlePaddle/PaddleDetection/)

<table>
  <tbody>
    <tr>
      <td width="35%">
        <figure style="width:95%">
          <img src="images/system/ppyoloe_plus_mscoco_comparison.png"
            alt="ppyoloe_plus_mscoco">
          <figcaption style="text-align: center;font-style: italic;">MS COCO performance comparison <a href="https://github.com/PaddlePaddle/PaddleDetection/tree/release/2.7/configs/ppyoloe">🡵</a></figcaption>
        </figure>
      </td>
      <td>
        <figure style="width:95%">
          <img src="images/system/ppyoloe_architecture.png"
            alt="ppyoloe_architecture">
          <figcaption style="text-align: center;font-style: italic;">PP-YOLOE architecture <a href="https://arxiv.org/abs/2203.16250">🡵</a></figcaption>
        </figure>
      </td>
    </tr>
  </tbody>
</table>

### Module 2: Detect text box on traffic signs

- Model: [**PP-YOLOE+**](https://arxiv.org/abs/2203.16250) from [Paddle Detection](https://github.com/PaddlePaddle/PaddleDetection/)

<table>
  <tbody>
    <tr>
      <td width="35%">
        <figure style="width:95%">
          <img src="images/system/ppyoloe_plus_mscoco_comparison.png"
            alt="ppyoloe_plus_mscoco">
          <figcaption style="text-align: center;font-style: italic;">MS COCO performance comparison <a href="https://github.com/PaddlePaddle/PaddleDetection/tree/release/2.7/configs/ppyoloe">🡵</a></figcaption>
        </figure>
      </td>
      <td>
        <figure style="width:95%">
          <img src="images/system/ppyoloe_architecture.png"
            alt="ppyoloe_architecture">
          <figcaption style="text-align: center;font-style: italic;">PP-YOLOE architecture <a href="https://arxiv.org/abs/2203.16250">🡵</a></figcaption>
        </figure>
      </td>
    </tr>
  </tbody>
</table>

## Samples

<table>
  <tbody>
    <tr>
      <td>#1</td>
      <td><img src="images/samples/sample_1.gif" alt="sample_1"></td>
    </tr>
    <tr>
      <td>#2</td>
      <td><img src="images/samples/sample_2.gif" alt="sample_2"></td>
    </tr>
    <tr>
      <td>#3</td>
      <td><img src="images/samples/sample_3.gif" alt="sample_3"></td>
    </tr>
  </tbody>
</table>
