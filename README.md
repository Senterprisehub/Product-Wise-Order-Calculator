# Product-Wise-Order-Calculator
The application is a web-based tool designed to help users, likely in sales or distribution, manage and calculate product orders. It presents a dynamic interface where users can input and track various product attributes.

Core Functionality:

Data Entry and Calculation: The main part of the app is an interactive table where you can add and modify product data. Each row represents a product with fields for "Case Size," "Box Pack," "SKU Name," and "PTS Value."

Order Quantity: For each product, you can enter a quantity in either "Unit(strip)" or "Unit(box)." The application then automatically calculates the "Box Value," "Strip Value," and the final "Net Bill Amount" based on the entered values and a Changeable 12% tax/margin factor.

Dynamic Updates: As you change any of the input fields, the calculations and the visual representations are updated in real-time.

Order Management: You can use the "Add Product" button to introduce new items to the order and the "Delete" button to remove them.

Save and Reset: The "Save Changes" button locks the core product information (like PTS value and SKU) while keeping the quantity fields editable. This allows you to finalize product prices while still being able to adjust the order size. The "Reset" button clears all user-defined quantities and unlocks all fields, returning the app to its initial state.

Visuals and User Experience:

Summary Panel: A summary card provides a quick overview of the"Total Order Value (Without Tax), "Total Order Value" and the "Total Order Value (in Lakhs)."

Interactive Pie Chart: A key feature is the animated pie chart, which visually represents the "Relative Net Bill Amount." This chart shows the proportional contribution of each product to the total order value, making it easy to identify which items are the biggest revenue drivers.

Responsive Design: The layout is fully responsive, adapting to both desktop and mobile screen sizes. On smaller screens, the table transforms into a cleaner, card-based view to ensure readability and ease of use.

Animations: The entire app incorporates subtle animations, from the main content fading in to the smooth drawing of the pie chart. This makes the user experience more engaging and modern.
