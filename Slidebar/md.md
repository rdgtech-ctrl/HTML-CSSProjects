position:fixed; in CSS is used to fix an element to a specific position on the screen,and it does nto move when you scroll

sticky position moves when you scroll and when it reaches a specific position then sticks itself


line-height:60px;
If the element is a single line of text, it will be vertically centered inside a 60px high area.

It's commonly used to vertically align text when there's no padding or height, especially in navbars or headers.


#check:checked~.sidebar_menu {
    left: 0px;
}


Action	Checkbox #check	Sidebar left	Result
Page loads	Not checked	-280px	Sidebar hidden
Bars icon clicked	✅ Checked	0px	Sidebar slides in
Close icon clicked	❌ Unchecked	-280px	Sidebar slides out

opacity:0; This means the element is fully invisible 
It's 100% transparent

opacity:1; This means the element is fully visible 
It's no transparent fully opaque