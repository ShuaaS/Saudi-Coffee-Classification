<img width="100" alt="Picture1" src="https://github.com/ShuaaS/Saudi-Coffee-Classification/assets/143282158/4e09f356-8a04-476f-8506-ff72c78ed436"> 
<img width="215" height="79" alt="QU" src="https://github.com/user-attachments/assets/9754b402-e21d-4da5-9b2d-33e3d2e88e6f" />
<img width="217" height="118" alt="Ed" src="https://github.com/user-attachments/assets/b8ddeedd-be8f-4e9b-aece-85826147cb52" />


# Saudi-Coffee-Classification  

 Saudi Coffee Beans Classification (Type and roasting) based on squeeze vision transformer.   

This repository contains the dataset alongside the codes written and implemented for the paper: 

_**“Classification of Saudi Coffee Types and Roasting Levels Using Squeeze Vision Transformer, Haifa F. Alhasson and Shuaa S. Alharbi 2024’’**_


# Dataset Distribution

We formed the data collected into three datasets based on the purpose needed
to be classified as follows:

**1- Saudi Coffee Types Dataset (SCTD):**
This dataset's primary goal is to differentiate between several Saudi coffee genotypes, which are related to Arabic coffee genotypes and differ in size and morphology. Five classes of Saudi coffee genotype beans (Harari, Khawlani, Nabari, Laqamti, and Wild (Briah)) are included in this dataset. In order to assess and manage the quality of the traded coffee beans, this dataset may be used to categorize beans according to variations in the shape characteristics of the genotypes of the beans. 


**2- Saudi Coffee Roasting Dataset (SCRD):**
This dataset's primary goal is to differentiate between various roast levels of Saudi coffee using samples taken from the country's coffee market. As we discover, there are three primary roasting levels in addition to the bean's raw form. The color of the beans makes them distinctive. Four classes of Saudi coffee genotype beans (Raw, Degree 1, Degree 2, and Degree 3) are included in this dataset.

**3- Saudi Coffee Types and Roasting Dataset (SCTRD):**
Two classes from the two intercross datasets were joined in this dataset to create 20 classes.


## An example of several types and roastings of Saudi coffee images:
<div align="center">
  <figure style="text-align: center; margin: 0;">
   <img width="80%" alt="Screen Shot 2024-06-21 at 4 11 17 PM" src="https://github.com/ShuaaS/Saudi-Coffee-Classification/assets/143282158/55ad754d-51a7-497a-b56e-d14c6ff1eb21">
  </figure>
</div>

## This Table provides information on the quantity of photos in each category:

<table>
  <thead>
    <tr>
      <th>Type of Coffee</th>
      <th>Raw</th>
      <th>Degree 1</th>
      <th>Degree 2</th>
      <th>Degree 3</th>
      <th>Total Num of Images</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Harari</td>
      <td>621</td>
      <td>600</td>
      <td>546</td>
      <td>762</td>
      <td>2529</td>
    </tr>
    <tr>
      <td>Bariah</td>
      <td>810</td>
      <td>678</td>
      <td>810</td>
      <td>604</td>
      <td>2902</td>
    </tr>
    <tr>
      <td>Khowlani</td>
      <td>408</td>
      <td>702</td>
      <td>588</td>
      <td>648</td>
      <td>2346</td>
    </tr>
    <tr>
      <td>Legamti</td>
      <td>522</td>
      <td>438</td>
      <td>491</td>
      <td>564</td>
      <td>2015</td>
    </tr>
    <tr>
      <td>Nabari</td>
      <td>556</td>
      <td>660</td>
      <td>696</td>
      <td>606</td>
      <td>2518</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <th colspan="5">Total images in all categories</th>
      <th>12310</th>
    </tr>
  </tfoot>
</table>

---

# Download dataset:

**Original (without crop)** click here: https://drive.google.com/file/d/1Bo3DzVeFUaYzjUBHM-6IA4u8TeaKDa3H/view?usp=sharing

**SCTD** click here: https://drive.google.com/file/d/1I29CIBTl77BNZqeNEMskxuLDoaJSFpne/view?usp=sharing

**SCRD** click here: https://drive.google.com/file/d/1HTyk-zRavcISvZVQLGhAWlOTDarKKGKT/view?usp=drive_link

**SCTRD** click here: https://drive.google.com/file/d/1SFbBcjtcuqgHbQjeL2O_ULXbChz7LwXc/view?usp=drive_link
__________________________________________________________________________________________
This research was funded by the “Saudi coffee grants” program offered by the Saudi Ministry of Culture. All opinions expressed herein belong to the researchers and do not necessarily reflect those of the Ministry of Culture.

If you find this code useful in your research and development, please reference this repository and the paper.

# Reference:
Alhasson, Haifa F., and Shuaa S. Alharbi. "Classification of Saudi Coffee beans using a mobile application leveraging squeeze vision transformer technology." Neural Computing and Applications (2025): 1-21.

This research was conducted collaboratively by two authors, representing the Department of Information Technology, College of Computer, Qassim University, and the Ministry of Culture.

This repositoty is under a GNU General Public License v2.0 (see included "LICENSE" file).
For any inquiry, please contact us via email: saudi.coffee.project@gmail.com

