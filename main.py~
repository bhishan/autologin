import mechanize #sudo pip install python-mechanize

br = mechanize.Browser() #initiating a browser 

br.set_handle_robots(False) #ignore robots.txt file

br.addheaders = [("User-agent","Mozilla/5.0 (X11; U; Linux i686; en-US; rv:1.9.2.13) Gecko/20101206 Ubuntu/10.10 (maverick) Firefox/3.6.13")] #user agent

login_page = br.open("http://school.dwit.edu.np/login/index.php")  #opening the login page

br.select_form(nr = 0)  #form index

br["username"] = "username" #the key "username" is the variable that takes the username/email value 

br["password"] = "password"    #the key "password" is the variable that takes the password value

logged_in = br.submit() #submitting the form (logging in) 

