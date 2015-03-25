# JoinDateIntervals
this is a basic java class that Join Date Intervals

# Credits

Gets inspiration from <http://sametmax.com/union-dun-ensemble-dintervalles/>

# Usage

```
List<Date> datesDebut = new ArrayList<Date>();
List<Date> datesFin = new ArrayList<Date>();
/*
* populates the dates lists here
*/
List<Range<Date>> ranges = JoinIntervals.joinDateIntervals(datesDebut, datesFin);
```

returns a collection of com.google.common.collect.Range objects
