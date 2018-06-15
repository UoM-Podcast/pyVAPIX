# pyVAPIX

## Usage:

print the vapix version and move to the set home position:
````
import pyvapix

vap = pyvapix.Vapix('10.99.89.49', 'username', 'password')
print vap.get_vapix_version()
vap.move('home')

````