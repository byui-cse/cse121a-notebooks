# cse121a-notebooks
## Winter Semester 2021

This repository is for sharing Clojure tasks and code.

For example:
```
(def phrase "Facetiously speaking, what is special about May the fourth?")

(require '(clojure [string :as s]))

(def num-different-letters
    (count (set (map str (seq (char-array (s/replace (s/upper-case phrase) #"[, ?]" ""))))))
```
