# qrcode generator
Develop a python program to generate QRcode for various data inputs,show casing proficiency in using librarie 
step1:Check wheather the python is install or not 
  ->In CMD type the command just python --version

step2:Install the qrcode module
  ->In CMD type the command 
	pip install qrcode

step3:Import into the program
  ->whenever you want the module import it like shown below
		from qrcode import *
			or
		import qrcode


Example:
	import qrcode
	v=qrcode.make("This QRCODE is prepared in PYTHON.")
	v.save("docpy.png")
	v.show()
