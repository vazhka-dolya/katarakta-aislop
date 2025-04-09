# katarakta-aislop
Separate version of [katarakta](https://github.com/vazhka-dolya/katarakta) that has features for training and using (sloppy) AI models. Made just for [this one video](https://www.youtube.com/watch?v=v_Xpv41m_0E). Based on [Public Test 4](https://github.com/vazhka-dolya/katarakta/releases/tag/vpt4).
<p align="center">
  <img src="https://github.com/vazhka-dolya/katarakta-aislop/blob/main/GitHubImg/aislop1.png" width="320"/>
</p>

# How to use
## Opening
Keep in mind that this version takes more time to open. When it does open, go to **Options**, then **Utilities**, and **AI Slop Creator**.
## Training
In the **Train model** tab, press **Select dataset folder…** and select a folder where your AI model's training data will be, the program already has one folder like that. Press **Open** to quickly access the dataset, put some images (all need to be the exact same resolution, otherwise you may experience errors) inside the **images** folder, and then press **Refresh** and you should see them appear in the program. Double-click **Description** column to give an image a description. When you're done, don't forget to click **Save**. After that, give the model a file name, set the epochs (the more, the better. Around 1000–1500 should be more than enough if it's not a big dataset), and press **Train**. If you followed the instructions correctly, you should now have a model.
## Running
This is pretty straightforward — just choose your model with **Select model…**, write a promp, and hit **Run**. Your generated textures will appear under **History**. Note that you can train textures that are not eyes or CHMB, it's just that I was too lazy to add functionality to apply them as something else, and you have to manually rename them. Everything else is self-explanatory.
