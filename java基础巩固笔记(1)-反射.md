aaaaaaa

## <asadas>

## 《撒大声地》

## 傻傻(sadas)

## sad（实打实）

>* Let v be partitioning item a[lo].
>* Scan i from left to right.
  - (a[i] < v): exchange a[lt] with a[i]; increment both lt and i
  - (a[i] > v): exchange a[gt] with a[i]; decrement gt
  - (a[i] == v): increment i


>* Let v be partitioning item a[lo].
>* Scan i from left to right.
  - (a[i] < v): exchange a[lt] with a[i]; increment both lt and i
  - (a[i] > v): exchange a[gt] with a[i]; decrement gt
  - (a[i] == v): increment i



>* Shuffle the array.
>* Partition(切分) so that, for some j
>*    - entry a[j] is in place
>*    - no larger entry to the left of j
>*    - no smaller entry to the right of j
>* Sort each piece recursively.
