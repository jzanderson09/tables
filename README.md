# [Structuring Planet Data (MDN)](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Structuring_planet_data)
### [The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-tables)
### [Github](https://github.com/jzanderson09/tables)

### **Starting point**

To start the assessment, make local copies of [blank-template.html](https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/blank-template.html), [minimal-table.css](https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/minimal-table.css), and [planets-data.txt](https://github.com/mdn/learning-area/blob/main/html/tables/assessment-start/planets-data.txt) in a new directory in your local computer.

### **Project brief**

You are working at a school; currently your students are studying the planets of our solar system, and you want to provide them with an easy-to-follow set of data to look up facts and figures about the planets. An HTML data table would be ideal — you need to take the raw data you have available and turn it into a table, following the steps below.

### **Steps to complete**

The following steps describe what you need to do to complete the table example. All the data you'll need is contained in the `planets-data.txt` file. If you have trouble visualizing the data, look at the live example below, or try drawing a diagram.

1. Open your copy of `blank-template.html`, and start the table off by giving it an outer container, a table header, and a table body. You don't need a table footer for this example.

2. Add the provided caption to your table.

3. Add a row to the table header containing all the column headers.

4. Create all the content rows inside the table body, remembering to make all the row headings into headings semantically.

5. Ensure all the content is placed into the right cells — in the raw data, each row of planet data is shown next to its associated planet.

6. Add attributes to make the row and column headers unambiguously associated with the rows, columns, or rowgroups that they act as headings for.

7. Add a black [border](https://developer.mozilla.org/en-US/docs/Web/CSS/border) just around the column that contains all the planet name row headers.

### **Hints and tips**
* The first cell of the header row needs to be blank, and span two columns.
* The group row headings (e.g. *Jovian planets*) that sit to the left of the planet name row headings (e.g. *Saturn*) are a little tricky to sort out — you need to make sure each one spans the correct number of rows and columns.
* One way of associating headers with their rows/columns is a lot easier than the other way.

### **Example**

The finished table should look like this:

![finished table](finished_table.png)

You can also [see the example live here](https://mdn.github.io/learning-area/html/tables/assessment-finished/planets-data.html) (no looking at the source code — don't cheat!)