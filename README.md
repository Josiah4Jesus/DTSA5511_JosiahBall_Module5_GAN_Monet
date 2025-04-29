# DTSA5511_JosiahBall_Module5_GAN_Monet

<p><strong>Name: </strong>Josiah Ball<br>
<strong>Date: </strong>4/29/2025<br>
<strong>Course: </strong>DTSA 5511</p>

<p>The purpose of this lab is to glorify Jesus Christ by creating a generative adversarial network (GAN) that generates 7,000 to 10,000 Monet-style images, in submission to the <a href="https://www.kaggle.com/competitions/gan-getting-started/overview" target="_blank">"I’m Something of a Painter Myself" Kaggle competition</a> [1]. The intended audience of this project is my fellow students at the University of Colorado at Boulder as well as the Kaggle co-competitors. Due to time constraints, this lab was heavily reliant on ChatGPT for the specific code of the GAN model, though all implementation and model parameter choices were the author's.[2] Comments in model code are author's to display understanding.</p>

<p><strong>NOTE: </strong>I sadly ran out of time on this assignment :( So the model is incomplete. But this notebook reflects my current understanding and as far as I could get into implementing.</p>

## The Problem

<p>The goal of this project is to create a generative adversarial network (GAN) that generates 7,000 to 10,000 Monet-style images as well as accurately determine which images are real and which are fake.</p>

## The Dataset

<p>The training dataset is composed of 300 Monet paintings sized 256x256px, and the testing dataset is made up of 7,028 real photos sized 256x256px to which my 7,028 Monet forgeries will be added.</p>

## Discussion

<p><strong>Summary: </strong>In this notebook, we:</p>

<ul>
    <li>Overviewed the problem</li>
    <li>Explored the data</li>
    <li>Normalized the data</li>
    <li>Built a generator model</li>
    <li>Built a discriminator model</li>
</ul>

<p><strong>Limitations: </strong>Some of the limitations of this notebook include:</p>

<ul>
    <li>The GPU could not be configured, so we had to run on the CPU</li>
    <li>I ran out of time, so the model was not successfully built or tested</li>
</ul>

<p><strong>Next Steps: </strong>If we were to continue iterating, some possible next steps include:</p>

<ul>
    <li>Complete training the model</li>
    <li>Create images and test score by submitting to Kaggle competition</li>
    <li>Run on a machine with a GPU for faster iteration</li>
    <li>Experiment with differing architectures</li>
</ul>
