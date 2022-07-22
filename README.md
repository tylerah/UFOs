# Visualization of UFO Sightings Data Using HTML & Interactive JavaScript
## Overview of Project
The purpose of this project was to create a webpage that contained a dynamic table capable of filtering data pertaining to UFO sightings. The original webpage was able to filter the data by date only, however, the updated webpage is capable of filtering for multiple criteria. The criteria included are: date, city, state, country, and shape. 

## Results
The webpage includes input fields that ask the end-user to provide the information they desire to filter the data with. The webpage uses JavaScript to detect whether or not any input has been provided. As soon as the user provides an input and either presses enter or clicks out of the field, the table will automatically update to be filtered based on the provided input. 

Before the user provides any input, the input boxes display an example of acceptable input. The unfiltered table looks like the following image:

![Screen Shot 2022-07-21 at 11 33 33 PM](https://user-images.githubusercontent.com/104606662/180369861-11a78236-ccb1-4837-a414-c241f4b0e226.png)

Once the user provides input and presses enter, the table automatically updates based on the provided input. The following image shows an example of the table being filtered based on the input "el cajon" in the City input field. Note that the table updates regardless of whether all of the fields have been supplied with a specific input. 

![Screen Shot 2022-07-21 at 11 34 08 PM](https://user-images.githubusercontent.com/104606662/180370056-ed4b91a3-1958-4f03-8f49-f85451818085.png)

If the user provides additional input, the table will automatically update again. The following image shows an example of the table being filtered on the City input "el cajon" and the Shape input "triangle."

![Screen Shot 2022-07-21 at 11 37 43 PM](https://user-images.githubusercontent.com/104606662/180370463-1eec3f18-dca0-47f2-b459-72769468b45b.png)

## Summary
### Drawbacks
Overall, the webpage successfully accomplishes its purpose: to dynamically filter and display information pertaining to UFO sightings. However, there are several drawbacks to the webpage. The first is that the webpage is not adaptable to different screen sizes or devices. While it appears clean enough on a laptop screen, it likely is not easy to navigate on a phone or tablet due to the difference in size and dimensions. Another drawback is that there is little to no direction on how to use the filters and dynamic table. Because of this, the end-user may not realize that all inputs need to be fully lower-case or the table will not display the data. Additionally, there is no message indicating that the supplied input has no matches. Instead, the table simply displays nothing and the user may incorrectly assume the filters are broken. 

### Recommendations for Future Development
Based on the drawbacks described above, the following recommendations may drasitcally improve the use and functionality of this webpage. First, as the primary purpose of this webpage is to provide data regarding UFO sightings, it would be important to shore up the table so that it both recognizes errors (typos, incorrect data for the input field, etc.) and provides feedback to the user. This would help facilitate the ability for the user to correctly access the data they are interested in.

A second recommendation would be to make the webpage adaptable to all devices. Currently, the webpage will only display properly on a computer screen. However, it still struggles to look aesthetically pleasing if the user changes the size of their browser widnow. Likewise, the small screen and varying dimensions of a phone or tablet would similarly pose the same issue. The webpage would benefit from additional code to ensure that it is fully adaptable based on what device is being used to view the page. 

One final recommendation would be to create a form that can recieve input from the user. As the webpage seeks to help people better understand UFO sightings, it could better accomplish its purpose if it could recieve data from the users regarding their personal experiences with UFO sightings. However, if such a feature were to be implemented, it would be important to include this data in a separate table that displayed a disclaimer indicating that the data was provided by individuals who visited the webpage as it may or may not be as reliable as the original data currently displayed. 
