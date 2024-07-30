# Table:- 
 1. It is collection of rows and columns
 2. Table is grid organised in rows and   columns much like in spread sheet.
 3. To create table in html we use <table></table> tag.It is semantic tag.
 4. Here we are creating table row by row. 
 5. To create Table Row we use <Tr></Tr> tag.
 6. To create cells, HTML provides 2 tags.
        i) <Th></Th> Tag:- It is used to create Table heading cells.

        ii) <Td></Td> Tag:- It is used to create Table data cells.

7. To provide title or caption to the table we use <caption></caption> tag.

8. Caption tag we have to write with in table tag.

9. syntax:- 
            <table border="1">
                <caption>Employee Salary Table</caption>
                    <tr>
                        <th>Emp Id</th>
                        <th>Name</th>
                        <th>Salary</th>
                    </tr>
                    <tr>
                        <td>101</td>
                        <td>Tinku</td>
                        <td>50000</td>
                    </tr>
            </table>

# cell spanning:- 
 In html we have two ways to span the cells.

 1. Rowspan:- It is an attribute used to span the cells on row basis.

    rowspan="_____"    value=1,2,3....

 2. colspan:- It is an attribute used to span the cells on column basis.

    colspan="_____"    value=1,2,3....

# Note:- 
  1. Rowspan and colspan attribute we can use with <th></th> and <td></td> tag.
  2. We can together use rowspan and colspan attribute.
        Ex:- <td rowspan="5" colspan="3"></td> 
             <th rowspan="5" colspan="3"></th> 


# Attribute of table tag

1. border:- it is used to control the border width.

    border="1"

2. cellpadding:-It is an attribut which is used to create space between cell border and cell content.
   
    cellpadding="20"

3. cellspacing:- It is an attribute which is used to space outside the cell
  
   cellspacing="10"

4. rules:- It is used to collapse table border and cell border.
    rules="all"

# Thead, Tbody and Tfoot tag:
  # 1. Thead Tag:- 
            1. It is container tag.
            2. The top most part of our table we have to write with in 
            <thead></thead> tag.

  # 2. Tbody Tag:-
            1. It is container tag.
            2. Remaining body of our table we have to write with in 
            <tbody></tbody> tag.

 # 3. Tfoot Tag:- 
            1. It is container tag.
            2. The bottom most part of our table we have to write with in <tfoot></tfoot> tag.

# Note:- 
        thead,tbody and tfoot tag are highly recommended for better explanation of code and crawler understanding purpose.