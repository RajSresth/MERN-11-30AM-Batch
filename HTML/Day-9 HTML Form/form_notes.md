# HTML Form:-
    1. Forms are used to accept input from the user.

    2. To create forms in html we use <form></form> tag.

    3. In html form, to accept input from the user we use <input> tag. It is Non-container or unpair tag.
         <input type="______" >

    4. input tag we have to write within form tag.

# Attributes of input tag:

 # 1. Type :- 
        Type attribute is used to specify which type of data we can accept in that input field.
    Ex:-
        <input type="______">

        values:- i) text
                ii) tel
               iii) email
                iv) password
                 v) file multiple
                vi) date
               vii) time
              viii) datetime-local
                ix) color
                 x) range
                xi) search
               xii) url
              xiii) submit
               xiv) reset
                xv) number
               xvi) radio
              xvii) checkbox
             xviii) image
               xix) button
                xx) month
               xxi) week
              xxii) hidden

# 2. Name:- 
          Name attribute is used to provide name to the input field.

# 3. Value:-
          value attribute is used to provide initial value to the input field. or
          Value attribute is used to target value inside an input field.

# 4. Readonly:-
      It will make the input field as readonly used can not change the value, but can accesss the input field.

# 5. disabled:-
    It will make the input field as disabled user can not access the input field.

# 6. required:- 
    It will make the input field as required to be filled .If input field is empty form will not be submitted.

# 7. placeholder:- 
    It is used to provide hint to the user.

# 8.autofocus:-
    Whenever page reloads it will automatically focus an input field.
# 9. size:- 
    It is used to control the length of an input field.

    size="_____"  value=30 (number)

# 10. maxlength:- 
  The maxlength attribute specifies the maximum number of characters allowed in an input field.

  maxlength="_____"  value=16 (number)

# 11. minlength:- 
The minlength attribute specifies the minimum number of characters allowed in an input field.

  minlength="_____"  value=2 (number)

# 12. max:- 
  1. It is used with type= number,range 
  2. Max attribute specifies the maximum value of an input field.

  max="_____"  value=10 (number)

# 13. min:- 
  1. It is used with type= number,range 
  2. Min attribute specifies the minimum value of an input field.

  min="_____"  value=5 (number)

# 14. autocomplete:- 
  The autocomplete attribute specifies if browsers should try to predict the value of an input field or not.

  autocomplete="______"   value= on | off

# 15. step:- 
  step Attribute is used to set the discrete step size of an input tag. The default stepping value for number inputs is 1

  It works with :-
  
    number
    range
    date
    datetime-local
    month
    time
    week
# 16 accept:- 
    Accept Attribute is used to specify the file types that the input field can accept.

    accept="______"

    1. audio/*: The user can pick all sound files.
    2.video/*: The user can pick all video files.
    3. image/*: A valid media type, with no parameters. 
    4. .png


# Label Tag:- 
  1. Label tag is used to connect text with the input field.
  2. The text we want to connect we have to write within label tag.
  3. It is container tag.
  4. In input tag, we have to use id attribute and that id's value we have to pass to label's for attribute.
  5. Whenever user click on that text respective input field will be focused.

  6. syntax:-
        <label for="username">Name</label>
        <input type="text" id="username">

# Fieldset Tag:
  1. Fieldset Tag is used to group form control and it will create one box around the group.
  2. It is container Tag.
  3. Fieldset Tag we have to write with in Form Tag.

# Legend Tag:
  1. It is container Tag.
  2. To provide title or caption to the fieldset we use legend tag.
  3. Legend tag we have to write with in Fieldset Tag.

syntax:- 
      <form action="">
          <fieldset>
                <legend>Registration Form</legend>         

              <label for="username">Name</label>
              <input type="text" id="username">
              <br><br>

          </fieldset>
      </form>

# Select Tag:
  1. It is container Tag.
  2. It is used to create dropdown list.
  3. To create dropdown list we use select tag.
  4. Here we are providing multiple options to the user from these option user can select only one option.
  5. To create Option we use Option Tag. It is container tag.
  6. syntax:- 

      <select name="State-name" id="">
        <option value="" selected disabled>--Select State Name--</option>
        <option value="Delhi">Delhi</option>
        <option value="Mumbai">Mumbai</option>
        <option value="Uttar Pradesh">Uttar Pradesh</option>
        <option value="Haryana">Haryana</option>
        <option value="Bihar">Bihar</option>
      </select>

# Disadvantage of Select Tag

    1. The main disadvantage of the select tag is that it limits the user's input options to the predefined list of options provided by the developer using the option tags.

    2. The user cannot enter any text of their choice or customize the options available in the list.


# DataList Tag: Autocomplete List/ Suggestion List

    1. The Datalist Tag is introduced in Html5.
    2. The Html datalist tag is used to provide an autocomplete feature on the form element.
    3. Datalist tag is a container tag.
    4. It is block level element.
    5. It is used to provide a list of predefined options to the users.
    6. Datalist tag is used to create suggestion list or autocomplete list.
    7. The <datalist> tag contains a set of <option> tags that define the options in the list.
    8. We are binding the suggestion list with the input field, for this we have to provide 'list' attribute in the input tag and 'id' attribute in the datalist tag, this same 'id' we have to provide in the 'list' attribute of input tag.
    9. Whenever the user inputs in the input field related suggestions are displayed.
    10. The advantage of using the datalist tag is that it allows users to enter values that are not present in the options list

    11. syntax:- 

      <input type="text" list="state-name" placeholder="Enter state name">

      <datalist id="state-name">
        <option value="Delhi"></option>
        <option value="Mumbai"></option>
        <option value="Uttar Pradesh"></option>
        <option value="Bihar"></option>
      </datalist>



# Textarea:- 
  1. It is container.
  2. It is used to accept multi line input from the user.

 # note:- when content is more inside the textarea, it will automatically create scroll bar.

 # Attributes of Textarea:-
 1. rows:- rows attribute is used to provide the dimension of height.
 1. cols:- cols attribute is used to provide the dimension of width.

 # syntax:- 
  <textarea rows="10" cols="30" name="" id=""></textarea>