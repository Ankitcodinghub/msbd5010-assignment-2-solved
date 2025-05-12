# msbd5010-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [MSBD5010 Assignment 2 Solved](https://www.ankitcodinghub.com/product/msbd5010-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91309&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MSBD5010  Assignment 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
Overview

The assignment is designed for investigating three typical segmentation methodologies, which are watershed segmentation algorithm, active contour model and Hough transform respectively. You cannot also use the built-in functions relating to the watershed algorithm, active contour model and circular Hough transform. All the work should be submitted via Canvas system.

Programming assignment specifics

Part 1: Watershed segmentation algorithm

You need to complete the implementation of the routine in my_watershed.m. It leverages the Watershed segmentation algorithm to segment all the circles in the input image. You are not allowed to use the watershed(), imdilate() ,or other related built-in functions for this question.

<ol>
<li>a) &nbsp;Given an inverse distance map of the input image, compute the segmentation label map using Watershed segmentation algorithm defined in the lecture notes. Assign 0 for ridge/dam and unique integer in [1, …, n] for each region.</li>
<li>b) &nbsp;Extract the ridge/dam pixels and set it to 1. Then, apply binary dilation to the ridge/dam map.</li>
<li>c) &nbsp;Superimpose the image of dilated ridge/dam map and original image to separate distinct circles in the original image.</li>
</ol>
The sample output for this task is shown below:

</div>
</div>
<div class="layoutArea">
<div class="column">
1/3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 2: Active contour model

You need to complete the implementation of the routine in my_active_contour.m. It leverages the snake contour model proposed by Kass etc. in 1988 to segment the leaf in the input image. You are not allowed to use the conv(), gradient(), imfilter(), fspecial(), circshift(), interp2(), or other related built-in functions for this question.

The sample output for this task is shown in Fig. 3:

Note:

<ol>
<li>You can suppose the weight 𝛼 and 𝛽 of the internal energy are uniform over
the snake.
</li>
<li>The function for generating the initial contour has been provided
(get_initial_contour.m). This function requires the user to left-click the mouse on the shown image to obtain the coordinates of control points for the initial contour. Then the initial contour will be generated automatically. Please right- click the mouse to stop the function. For the naïve snake model, the initial contour should be close to the object boundary, otherwise the final active contour will fail to converge to the desired location. The TAs will try their best to mark the control points as close as to the image boundary during grading.
</li>
<li>Please state the derivation process of the matrix A (Lecture note: image- segmentation-part-2). You can either write your statement in the provided comment area in the Matlab code, or write it down in a .txt file or .pdf file. (10%)</li>
<li>When updating the next locations of the contour, you are required to implement your own interpolation method. The nearest interpolation is not allowed to used. (10%)</li>
<li>For your reference: Kass, Michael, Andrew Witkin, and Demetri Terzopoulos. “Snakes: Active contour models.” International journal of computer vision 1.4 (1988): 321-331.</li>
</ol>
</div>
</div>
<div class="layoutArea"></div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Part 3: Hough transform

You need to complete the implementation of the routine in hough_transform.m that can be used to detect circles in a binary image with circular Hough transform. Given that the range of radii of the circles in the input image is [40, 80] pixels. You are not allow to use the imfindcircles() Matlab built-in function for this question.

a) Find the edge of the input image

b) Perform the circular Hough Transform and create a variable ‘Accumulator’ to store the bin counts. (10%)

c) Search for the highest count cells in the Hough accumulation array. (5%)

Sample run of the programming assignment

The main routine of the assignment including displaying the final results is well written in the msbd5010_assign2.m file. After completing all the functions, you are supposed to get figures on the screen when you run the command below in the MATLAB environment.

&gt;&gt; msbd5010_assign2;

</div>
</div>
<div class="layoutArea">
<div class="column">
3/3

</div>
</div>
</div>
