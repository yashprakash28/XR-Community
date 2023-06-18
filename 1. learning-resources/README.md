| Source | What is it about? | Type |
|:----------|:---------|:---------|
|[Unity-Learn](https://learn.unity.com/)|Official Unity Courses to get you started|Free|
|[Sebastian Lague](https://www.youtube.com/@SebastianLague)|Explore the potential of Unity and unlock new concepts|Free|
|[Brackeys](https://www.youtube.com/@Brackeys)|Beginner to expert guide for tools in Unity|Free|
|[MIT Computer Graphics](https://www.youtube.com/playlist?list=PLQ3UicqQtfNuBjzJ-KEWmG1yjiRMXYKhh)|Insight into the core concepts of Computer Graphics|Free|
|[Ajna Creator Program](https://www.ajnacreator.com/)|India’s first XR content creation program|Paid|
|[TechXR Courses](https://techxr.co/)|Wide range of coursware for different levels of expertise|Paid|
|[Getting Started with Spatial Experience Designing](https://twitter.com/OlamideTowobola/status/1665985887048540162?t=G2VqDcUkhoPCHeXEUEaVlg&s=08)|Product design, Graphic design, Web design, UX design, Webflow, Figma, UI/UX|Free|

## Tips for contributing

1. Adhere to the specified format as above.

<script>
// Wait for the page to load
window.addEventListener('DOMContentLoaded', (event) => {
  // Get the table element
  const table = document.querySelector('table');

  // Get the table rows and convert them to an array
  const rows = Array.from(table.getElementsByTagName('tr'));

  // Sort the rows based on the text content of the first column
  const sortedRows = rows.sort((a, b) => {
    const textA = a.cells[0].textContent.trim();
    const textB = b.cells[0].textContent.trim();
    return textA.localeCompare(textB);
  });

  // Remove existing rows from the table
  rows.forEach((row) => {
    table.removeChild(row);
  });

  // Add the sorted rows back to the table
  sortedRows.forEach((row) => {
    table.appendChild(row);
  });
});
</script>
