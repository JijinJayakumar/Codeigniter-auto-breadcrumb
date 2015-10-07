# Codeigniter-auto-breadcrumb
Codeigniter auto breadcrumb library for CI 2.2.2 or above

# Installation

1.Just merge the library into the approriate place, you can use it anywhere

2. To start using the library,
	- Open the library, check the Template() function inside it,
	- edit the embedded html as well as you want. 
	- There are some additional static link that will appear on rightside of the primary breadcrumb, you also can use it.
	- to start the auto-breadcrumb, just echo $this->breadcrumb->generate() on you view or
	- $data['breadcrumb'] = $this->breadcrumb->generate(); from your controller

3. Enjoy the library anywhere
