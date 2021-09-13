<div id="adobe-dc-view"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{promise: "<FILE_BLOB_PROMISE>"},
			metaData:{fileName: "<FILE_NAME>"}
		}, {});
	});
</script>

# About
This repository contains project work for Udacity's Data Analyst Nanodegree

# Program Syllabus  

## Part 1: Welcome to the Nanodegree program!
Welcome to the program! In this part, you’ll get an orientation into using our classroom and services. You’ll also get advice for making the best use of your time while enrolled in this program.
- Project: Explore Weather Trends

## Part 2: Introduction to Data Analysis
Learn the data analysis process of questioning, wrangling, exploring, analyzing, and communicating data. Learn how to work with data in Python using libraries like NumPy and Pandas.
- Project: Investigate a Dataset

## Part 3: Practical Statistics
Learn how to apply inferential statistics and probability to important, real-world scenarios, such as analyzing A/B tests and building supervised learning models.
- Project: Analyze A/B Test Results

## Part 4: Data Wrangling
Learn the data wrangling process of gathering, assessing, and cleaning data. Learn how to use Python to wrangle data programmatically and prepare it for deeper analysis.
- Project: Wrangle and Analyze Data

## Part 5: Data Visualization
Learn to apply sound design and data visualization principles to the data analysis process. Learn how to use analysis and visualizations to tell a story with data.
- Project: Communicate Data Findings  
