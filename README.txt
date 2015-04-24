it all started with SOQIFKV12A58A7CC74

to make a dot file:

    ./find-children SOQIFKV12A58A7CC74 > test.dot

or you can do a bunch:

    ./find-children SO* > test.dot

to make an svg:

    dot -Tsvg test.dot -o outfile.svg 

