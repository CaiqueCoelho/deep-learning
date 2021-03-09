# Fastai Chp 6 talk, resources  

### 1. Multiclass Classification  

### 2. Regression, continuous variable  

 * 2.a  Middle of face, not nose.  

### 3. Data Pre-Processing, Pandas, Regular Expression, Fastai  
  * Pandas cheatsheet  
  * Vanderplas book  
  * McKinney book  
  * Regular Expression website - also many games  
  * Fastai DataBlock, Data Loader, Tutorials  

### 4. Group Project Proposal - Planet 2017 Kaggle Challenge  
 * Show how to download from Kaggle  
   - https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data  
   - Project Proposal:  https://github.com/JennEYoon/geo-ml/blob/main/rainforest/proposal.md  
   - Slack new channel - join by browsing for channel, **Amazon Rainforest**  
 * tif, jpg, and convert to rgb  
   ```python  
   from PIL import Image
   im = Image.open(f)
   #im  # Get error message
   print(im.mode)  # Output: CMYK

   if im.mode == 'CMYK': 
    rgb_image = im.convert('RGB')
    
   rgb_image  
   # Add .show() if not running in a Jupyter notebook
   ```
   - sample notebook:  https://github.com/JennEYoon/geo-ml/blob/main/rainforest/nbs-planet/data-sample-test1.ipynb   
 * My geo-ml repo: https://github.com/JennEYoon/geo-ml  
   - Caution: May move folders around and temporarily rename repo to perform cleanup.  
   - Repo size getting close to 1 GB, made the mistake of pushing many image files.  
 * \-\-\-    
 * Contact info: Jennifer Yoon, jenneyoon@gmail.com, datasciY.com
   Github:  https://github.com/JennEYoon  
   Leesburg, Virginia, USA
   
