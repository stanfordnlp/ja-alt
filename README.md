# ja-alt
Updates to the Japanese section of ALT (Asian Language Treebank)

With assistance from Prof. Maekawa, we made some edits to remove
things that were not in the expected tag set.  For example, there were
instances when NN was treated as a constituent or syntactic tag, such
as `(NN (`, which we edited to `(NP (`.  Other similar changes fixed
tag errors in both POS and syntactic tags.  Finally, some but not all
of the double white spaces were edited out; contexts where the space
might cause tokenization changes were not changed.
