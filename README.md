# Media-Rating-Exercise
This is a small exercise demonstrating how video sources, datalists and various media components are used in HTML.

# Explanation
* The video element has a controls attribute to enable the video player controls (pause, volume, timeline, and so on).
* The video element contains a source element. The source element has a src attribute which specifies the video file to be played. It also has a type attribute to specify the video type, in this case it is an MP4 file.
* The input type for the rating is set to range.  This will present a slider in the web browser. The min attribute is set to 1 and the max attribute is set to 5. The default range is 0 to 100 so these attributes need to be set so that the slider range matches the datalist.
* The range input has a list attribute set to ratings. This matches the id attribute of the datalist element below the input element.
* The datalist element contains the possible slider value and the corresponding label to display. When no label is specified for a value, no label will display on the slider for that value.
