[# css
HTML and CSS for dropdown 
]
(https://roadmap.sh/projects/custom-dropdown)
https://roadmap.sh/projects/custom-dropdown


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dropdown Menu</title>
  <style>
    /* Basic styling for the dropdown container */
    .dropdown {
      position: relative;
      display: inline-block;
    }
    /* Style for the dropdown button */
    .dropdown-button {
      background-color: rgb(54, 99, 224);
      color: whitesmoke;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }
    /* Styling the dropdown menu itself */
    .dropdown-content {
      display: none;
      position: absolute;
      background-color: whitesmoke;
      min-width: 160px;
      box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
      z-index: 1;
    }
    /* Style for the items in the dropdown */
    .dropdown-content a {
      color: black;
      padding: 12px 16px;
      text-decoration: none;
      display: block;
    }
    /* Change background color of links on hover */
    .dropdown-content a:hover {
      background-color: #8fcef5;
    }
    /* Show the dropdown content when hovering over the button */
    .dropdown:hover .dropdown-content {
      display: block;
    }
    /* Change button color on hover */
    .dropdown:hover .dropdown-button {
      background-color: rgb(69, 197, 229);
    }
  </style>
</head>
<body>
  <div class="dropdown">
    <button class="dropdown-button">Dropdown</button>
    <div class="dropdown-content">
      <a href="#item1">Item 1</a>
      <a href="#item2">Item 2</a>
      <a href="#item3">Item 3</a>
    </div>
  </div>
</body>
</html>
