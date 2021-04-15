# ArtCoder: An End-to-end Method for Generating Scanning-robust Stylized QR Codes
A terrible PyTorch implementation of "***ArtCoder: An End-to-end Method for Generating Scanning-robust Stylized QR Codes***".

The paper "***ArtCoder: An End-to-end Method for Generating Scanning-robust Stylized QR Codes***" has been accepted by CVPR 2021. If the work or code is useful to you, please cite
```
@inproceedings{yamato1992recognizing,
  title={ArtCoder: An End-to-end Method for Generating Scanning-robust Stylized QR Codes.},
  author={Hao Su, Jianwei Niu, Xuefeng Liu, Qingfeng Li, Ji Wan, Mingliang Xu, Tao Ren},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition},
  year={2021}
}
```

## abstract
Quick Response (QR) code is one of the most worldwide used two-dimensional codes. Traditional QR codes appear as random collections of black-and-white modules that lack visual semantics and aesthetic elements, which inspires the recent works to beautify the appearances of QR codes. However, these works adopt fixed generation algorithms and therefore can only generate QR codes with a pre-defined style. In this paper, combining the Neural Style Transfer technique, we propose a novel end-to-end method, named ArtCoder, to generate the stylized QR codes that are personalized, diverse, attractive, and scanning-robust.~To guarantee that the generated stylized QR codes are still scanning-robust, we propose a Sampling-Simulation layer, a module-based code loss, and a competition mechanism. The experimental results show that our stylized QR codes have high-quality in both the visual effect and the scanning-robustness, and they are able to support the real-world application.

## Results

<table>
 <tr>
   <td>Style</td><td>Output</td><td>Content</td>
 </tr>
  
 <tr height="400" valign="middle">
      <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/texture1.1.jpg" width="290" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_84.jpg" width="350" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/boy.jpg" width="290" />      </td>
 </tr>
  
 <tr height="400" valign="middle">
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/s55v2.jpg" width="290" /></td>
     <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_105.jpg" width="350" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/boy.jpg" width="290" />      </td>
 </tr>
  
 <tr height="400" valign="middle">
  <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/redwave4.jpg" width="290" /></td>
      <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_182.jpg" width="350" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/ca.jpg" width="290" />      </td>
 </tr>
 
  <tr height="400" valign="middle">
  <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/s6.jpg" width="290" /></td>
      <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_375.jpg" width="350" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/ca.jpg" width="290" />      </td>
 </tr>
  
 <tr height="400" valign="middle">
     <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/texture1.1.jpg" width="290" /></td>
     <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_66.jpg" width="350" /></td>
  <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/brad.jpg" width="290" />      </td>

 </tr>
 
 <tr height="400" valign="middle">
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/s41.2.jpg" width="290" /></td>
        <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_131.jpg" width="350" /></td>
   <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/man.jpg" width="290" />      </td>
 </tr>
 
 <tr height="400" valign="middle">
     <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/style/texture1.1.jpg" width="290" /></td>
     <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/demos/output_68.jpg" width="350" /></td>
  <td><div align=center><img src="https://github.com/SwordHolderSH/ArtCoder/blob/main/content/man.jpg" width="290" />      </td>


 </tr>
  

 

 

  
 
 </table>
  <p align="center"> **Table 1**</p>
