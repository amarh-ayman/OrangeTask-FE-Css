<div style="border: 1px solid beige; padding: 50px; text-align: center">
  <h1>OrangeTask-FE-Css</h1>
</div>

## Frontend Development Task - Burger Design and Responsiveness

### Objective:

The objective of this task is to assess the candidate's HTML and CSS skills, particularly in designing and styling elements using HTML and CSS only. The candidate will be required to create a visually appealing representation of a burger using HTML and CSS, and then make it responsive.

### Expected Final Result:

Please refer to the [expected final result](LINK_TO_EXPECTED_RESULT) for the visual representation of the burger design and responsiveness.

### Instructions:

1. Create a GitHub repository for this task.

2. Using HTML and CSS only, design and code a burger image as follows:

   - The burger should consist of various components, including buns, lettuce, tomatoes, cheese, and a patty. You are free to choose the design and colors for each component, but keep in mind that it should resemble a realistic burger.
   - The burger should be positioned at the center of the page.

3. Implement responsiveness:

   - Ensure that the burger remains centered within the viewport as it increases in size.
   - When the viewport width is smaller than the specified breakpoint, the burger should adapt and remain fully visible within the smaller viewport.
   - Utilize appropriate CSS techniques to achieve responsiveness, such as media queries.

4. Commit your code to the GitHub repository.

5. Provide a README.md file in the repository that includes:

   - Describe the CSS techniques you used to make the burger responsive.
   - Include any additional notes or considerations you think are relevant.

6. Submit your solution:
   - Once you have completed the task, share the GitHub repository link with us for review.
   - Make sure the repository is publicly accessible and includes all the necessary files.

### Evaluation Criteria:

- Accuracy in recreating a visually appealing burger using HTML and CSS only.
- Attention to detail and adherence to the provided instructions.
- Effective implementation of responsiveness using appropriate CSS techniques.
- Code quality, organization, and readability.
- Overall creativity and design choices.

### Note:

Feel free to explore additional features or improvements beyond the basic requirements if you have time.
Good luck, and we look forward to reviewing your submission!

##

# Final Result:

To see the final submission, [check out the GitHub](LINK_TO_EXPECTED_RESULT) repository containing the HTML and CSS code for the burger design and responsiveness.

README.md

# Burger Design and Responsiveness

In this project, I have created a visually appealing representation of a burger using HTML and CSS only. The objective was to design and style the burger components like buns, lettuce, tomatoes, cheese, and a patty to resemble a realistic burger. Additionally, I implemented responsiveness to ensure that the burger adapts and remains visually appealing across various screen sizes.

## CSS Techniques for Responsiveness

To achieve responsiveness, I utilized media queries, which allow specific CSS rules to be applied based on the screen size. Here are the CSS techniques I used:

### Media Query for Viewport Widths up to 768px

```css
@media (max-width: 768px) {
  .sandwich {
    height: 236px;
    width: 236px;
  }
  .sandwich .layer:not(.bottom_bun) {
    margin: 3px 0;
  }
  .sandwich:hover .layer {
    transform: scale(1.05) !important;
    margin: 5px 0;
  }
  .sandwich .layer.patty::before {
    left: 10px;
  }
}
```

- I set the `.sandwich` class to have a height and width of 236 pixels when the viewport width is up to 768px. This ensures the burger remains proportionate and visually appealing on smaller screens.
- The `.layer` class elements, except the bottom bun, have a small top and bottom margin of 3 pixels, creating a slight gap between the burger layers.
- When hovering over the burger (`.sandwich:hover .layer`), all the layers scale up by 5% and have a margin of 5 pixels on top and bottom. The `!important` rule ensures this transformation takes priority over other rules.
- For the `.layer.patty` class, I added a pseudo-element `::before` and adjusted its left position to 10 pixels. This positions the patty slightly to the right, enhancing the burger's visual appearance.

### Media Query for Viewport Widths up to 480px

```css
@media (max-width: 480px) {
  .sandwich {
    height: 280px;
    width: 257px;
  }
}
```

- For even smaller screens, up to 480px, I adjusted the `.sandwich` class to have a height of 280 pixels and a width of 257 pixels. This ensures the burger maintains its visual appeal and remains well-sized on mobile devices.

## Additional Notes

- I used only HTML and CSS for this project, ensuring a lightweight and fast-loading burger representation.
- The burger components' design and colors were carefully chosen to create an appetizing and visually appealing representation.
- I paid attention to details, ensuring that each layer of the burger is distinguishable and well-positioned.
- The burger remains centered within the viewport as the screen size changes due to the CSS techniques applied.
- The project is structured and organized to maintain code readability and understandability.

I thoroughly enjoyed working on this project and took care to meet the requirements and deliver a creative and responsive burger design using HTML and CSS only. I believe this submission demonstrates my proficiency in frontend development and ability to create visually appealing user interfaces.

Thank you for reviewing my submission!

## Image Submission:

Below is the Img submission

![Burger Image](images/burgerimg.png)
