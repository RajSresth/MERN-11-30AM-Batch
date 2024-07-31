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