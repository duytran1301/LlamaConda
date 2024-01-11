# LlamaConda
This is where you download the model to test run and run on. Here I put some tips for you to easier to do without having to google and find the result 
**based on the youtube** 
_https://www.youtube.com/watch?v=k2FHUP0krqg_

#please download the new version of anaconda so you can have the anaconda prompt

- conda create -n textgen python=3.10.9 #should be use this since pytorch support some old version only

- conda activate textgen

**# please check ther verion you download by simply find on pytorch **

- install pytorch: pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu117 


**#download git using conda if you haven't got git yet**
- conda install -c anaconda git

#now if you finish install git you should be fine with everything else
- git clone https://github.com/oobabooga/text-generation-webui
- cd text-generation-webui
- pip install -r requirements.txt
- python server.py
