# Challenge

In Java Entreprise those helper/utility classes such as MyCompanyStringUtil.java are usually a repository
of untested & unneeded code.

Your challenge here is to replace those utility methods (in MyCompanyUtil.java) with more robust 
third parties equivalent methods (ex: common-lang from Apache) using the __test/delegate/inline__ pattern

# Session

The trainer should provide an explanation of the test/delegate/inline pattern by performing it on one of the
utility methods from MyCompanyUtil.java.

ONce it is clear for the audience they will do the same on the others utility methods.

# Test / Delegate / Inline pattern

The goal of this method is to replace a method implementation with a better implementation 
__without any risks of braking functionnalities__.

### Step 1

Add unit test to the old method you have chosen to lake sure you fully test it and therefore understands everything
that this method is supposed to be doing.

### Step 2

Replace the implementation body of the old method with a new and better implementation (usually from a third party librairy).
The old method signature should be unchanged at this point.

### Step 3

Using your IDE perfom a INLINE of the method. It will INLINE perfectly if you new implementation in the old method body is a oneliner.



