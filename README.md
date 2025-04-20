# katarakta-aislop
Separate version of [katarakta](https://github.com/vazhka-dolya/katarakta) that has features for training and using (sloppy) AI models. Made for just [this one video](https://www.youtube.com/watch?v=v_Xpv41m_0E). Based on [Public Test 4](https://github.com/vazhka-dolya/katarakta/releases/tag/vpt4).
<p align="center">
  <img src="https://github.com/vazhka-dolya/katarakta-aislop/blob/main/GitHubImg/aislop1.png" width="320"/>
</p>

# How to use
## Opening
Keep in mind that this version can take *way* more time to open. When it does open, go to **Options**, then **Utilities**, and **AI Slop Creator**.

## Training
In the **Train model** tab, press **Select dataset folder…** and select a folder where your AI model's training data will be, the program already has one folder like that (`dataset`). Press **Open** to quickly access the dataset, put some images (the images need to be the exact same resolution, otherwise you may experience problems) inside the **images** folder, and then press **Refresh** and you should see them appear in the program. Double-click an image's **Description** column to give it a description that the AI will use for understanding the prompt. When you're done, don't forget to click **Save**. After that, give the model a file name, set the epochs (the more, the better. Around 1000–1500 should be more than enough if it's not a big dataset), and press **Train**. If you followed the instructions correctly, you should now have a model.

## Running
This is pretty straightforward — in the `Run model` tab, just choose your model with **Select model…**, write a prompt, and hit **Run**. Your generated textures will appear under **History**. Note that you *can* train textures that are not eyes or CHMB, it's just that I was too lazy to add functionality to apply them as something else, so you have to manually rename them. Everything else is self-explanatory.

# Building
I have used PyInstaller instead of Nuitka for this version since I think it's more reliable in this case. For some reason, it can build only if you do `--collect-all` for some of the modules. The wacky command that I used is in the `build-command.txt` file.

# Warning
This version of katarakta was made specifically for [one machinima](https://www.youtube.com/watch?v=v_Xpv41m_0E) and I never plan to use it again, hence I also don't plan on making any updates for it at all. This version was also a bit rushed, therefore I didn't make the AI Slop Creator window be able to be translated to other languages, and it lacks some other less important functionality as well. Though you are free to report any issues that you may find on the **Issues** tab, I am just not going to fix any of them.

I am uploading this simply for anyone who is curious and wants to play around with it for themselves. I am not uploading any of the models I have trained with it because they contain textures that weren't made by me.
