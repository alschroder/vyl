vyl
===

Runs 'vi' against one of the results of the last command you ran.

Example usage
=============

Basic case (one result):

<pre>
$ find . -name fred
./fred
$ vyl
----> vi now opens to edit the file ./fred
</pre>

Multiple results:

<pre>
$ find . -name fred
./fred
./src/fred
$ vyl 2
----> vi now opens to edit the file ./src/fred
</pre>

License
=======

vyl is release under the MIT license, please see the comments in vyl for the
full license text

