ABOUT Hash.php : 

# the function inside the file hash.php, generates a $apr1$ apache has , that is understandable by apache , most of the codes which are similar to this might give you errors, 
whenever you try to use this for authentication but this one won't, I personally tested it and it works fine , took it from a post on stackoverflow , so can't take any credits..

About .htaccess:

# The .htaccess file has code that when you put it in a directory the server will ask you for authentication, you would see two links inside it , one is the direcotry link
that you wanna put the password on , and the second is the link of the authfile .

# you can delete the auth file anywhere , but I would personally recommend to put it in the same directory because if that auth file is deleted by anyone accidently or
intentionally, then in clear words your directory will be fucked , you won't be able to use any file in that directory, and the only option you would have then is the cpanel.
