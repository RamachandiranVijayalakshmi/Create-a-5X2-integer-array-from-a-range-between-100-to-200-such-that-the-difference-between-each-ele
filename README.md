## Create-a-5X2-integer-array-from-a-range-between-100-to-200-such-that-the-difference-between-each-ele
## Sample code to check the details 
```sh
import numpy

print("Creating 5X2 array using numpy.arange")
sampleArray = numpy.arange(100, 200, 10)
sampleArray = sampleArray.reshape(5,2)
print (sampleArray)
```
## Example output
Creating 5X2 array using numpy.arange
[[100 110]
 [120 130]
 [140 150]
 [160 170]
 [180 190]]
