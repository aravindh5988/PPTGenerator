# PPT Generator

This module generates PowerPoint presentations from Mendix pages. It renders the selected page and places the result across slides using the chosen paper size and orientation. The slides preserve the page’s visual layout, text wrapping, and widget appearance. Each slide is embedded as an image, so its contents aren’t individually editable in PowerPoint.

## Dependencies

- Mendix Studio Pro 11.12.1
- Playwright for Java and Chromium, for rendering pages
- A Mendix page or template configured for export

## Configuration

- Configure the PPT Generator action with the page or template to export.
- Select a paper size and slide orientation.
- Ensure the page is available to the user running the export.
- Run the generation action and download the resulting `.pptx` file.
- Check the sample logic and pages in the UseMe folder.

## Screenshots
<img width="870" height="299" alt="First" src="https://github.com/user-attachments/assets/af46c48b-26b5-42ae-a332-4b0a1128105d" />
<img width="960" height="502" alt="Second" src="https://github.com/user-attachments/assets/d1f85194-9674-491e-9dda-4784df3f60e4" />
<img width="960" height="383" alt="Three" src="https://github.com/user-attachments/assets/2d695f25-01fe-411b-a232-0cd0c46d3313" />


