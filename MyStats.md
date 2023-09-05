# Akshay Kumar Gupta Attuluru
Hello, This is Akshay and I am from India.I am intrested in learning new things and exploring new places.I am basically want to see other happy or make other happy.

[My image](https://github.com/Attuluru/my2-Attuluru/blob/main/My%20Pic.jpg?raw=true)

--- 

# Sports Table 
Below table describes the sports that i would like to recommend and it conatins the data like Name of the sport and reason why you need to play and average hours you need to spend in the sport per week

This is the table

| Name of sport | Reason | Hours Per week |
| --- | --- | ---: |
| Tennis | For relaxing Ourselves | 7 |
| chess | Its a mind game  | 14 |
| Table tennis | To decrease our pressure | 10 |
| Golf | Its a rich game involing many techniques and ideas | 15 |

---

# Pithy Quotes 
```A friend is someone who knows all about you and still loves you.```-*Elbert Hubbard*

```Science is magic that works.``` -*Kurt Vonnegut*

---

# Code Fencing 

```How to sort Sass properties (for example in alphabetical order)```[QuickLink by stackoverflow](https://www.bing.com/search?q=sorting+function+using+Sass+code&form=QBLH&sp=-1&ghc=1&lq=0&pq=sorting+function+using+sass+code&sc=10-32&qs=n&sk=&cvid=07DEFC965E5248C8A301E1365966849D&ghsh=0&ghacc=0&ghpl=)

```
/// Quick sort
/// @author Sam Richards
/// @param {List} $list - list to sort
/// @return {List}
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}

```
[Snippet code Link](https://css-tricks.com/snippets/sass/sorting-function/)