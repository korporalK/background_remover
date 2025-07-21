Advanced Image Background Remover
An advanced, client-side web tool to remove image backgrounds. Features multi-color selection, tolerance and feathering controls, a zoomable live preview, and multiple export formats. Built with pure HTML, JavaScript, and Tailwind CSS.

✨ Features
Client-Side Processing: All processing happens in your browser. Your images are never uploaded to a server, ensuring 100% privacy.

Multi-Color Selection: Click on the original image to select multiple colors to remove.

Tolerance Control: Fine-tune the sensitivity for each selected color to remove more or fewer similar shades.

Feathered Edges: Use the "Blur Edge" slider to create a soft, anti-aliased edge for a more natural blend.

Zoom & Pan: Independently zoom and pan on both the original and preview images to inspect details with precision.

Live Preview: See the result of your changes instantly.

Multiple Export Formats: Download your final image as a PNG, JPEG, or WebP.

Quality Control: Adjust the output quality for JPEG and WebP to manage the file size.

Dynamic Filenames: The downloaded file is automatically named based on the original filename (e.g., logo.png becomes logo-transparent.png).

Fully Responsive: The user interface is designed to work seamlessly on desktop, tablets, and mobile devices.

🚀 How to Use
Save the Code: Save the index.html file provided in the project.

Open in Browser: Open the file in any modern web browser like Chrome, Firefox, or Edge.

Upload Image: Click "Upload Image" and select your file.

Pick Colors: Click on the different colors/shades in the original image (left panel) that you want to remove. Each click will add a new color to the settings panel.

Adjust Settings: For each selected color, use the Tolerance and Blur Edge sliders to perfect the selection.

Inspect the Result: Use the zoom and pan controls on the "Live Preview" panel (right) to check the result.

Choose Download Options: Select your desired format (PNG, JPEG, WebP) and adjust the quality if needed.

Download: Click the "Download Image" button to save the final image to your computer.

🛠️ Tech Stack
HTML5: For the core structure of the application.

Tailwind CSS: For all styling and creating a responsive layout.

JavaScript (ES6+): For all the application logic, including DOM manipulation and image processing.

HTML5 Canvas API: Used for reading pixel data, creating the alpha mask, applying filters, and compositing the final image.

🔒 Privacy
This tool is built with privacy as a top priority. No image data ever leaves your computer. The entire process, from uploading to final rendering, is handled locally in your web browser.