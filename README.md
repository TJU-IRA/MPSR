# MPSR
MPSR is a Multi-scale Perception Network for Infrared Image Super-Resolution. The code will be made public after the acceptance of the paper.
## Requirements
1.Python 3.10  

2.Opencv  

3.Pytorch 1.13.0  

4.torchvision  

5.imageio  

6.skimage

### Quick start
1.Clone this repository:  
git clone https://github.com/TJU-IRA/MPSR.git  
2.Download our pre-trained models from the links below, unzip the models and place them to <td bgcolor=gray>./models. </td>

<table class="tg"><thead>
  <tr>
    <th class="tg-c3ow">Scale</th>
    <th class="tg-c3ow">Link</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-c3ow">x2</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">x4</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
  <tr>
    <td class="tg-c3ow">x8</td>
    <td class="tg-c3ow"><a href="https://drive.google.com/drive/folders/1jq6xowAfEymklsMCwllfrJ26723_yBcR?usp=sharing" target="_blank" rel="noopener noreferrer">[GoogleDrive]</a></td>
  </tr>
</tbody>
</table>
3.Then, cd to <td bgcolor=gray>MPSR</td> and run  following commands for evaluation on IRAB-T:  
python test.py -opt options/test/test.yml  

4.Finally, you can find the reconstruction images in <td bgcolor=gray>./results .  

### Results
![alt text](https://github.com/TJU-IRA/MPSR/blob/main/Fig/Qualitative.png)
### TODO
Curriculum learning for complex degradation models (i.e. BD and DN degradation models).

 

