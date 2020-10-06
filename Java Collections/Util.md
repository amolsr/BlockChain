#### Some Handy Conversion

       Array to List
         List<Integer> arr= Arrays.stream(A).boxed().collect(Collectors.toList());
       List to Array
         int[] array = list.stream().mapToInt(i->i).toArray();

#### Print an list

       list.forEach(System.out::print);

#### Fill 0-3 in array arr.

       Arrays.fill(arr, 0, 3, -1 )

#### Fill as per a condition.

       Arrays.setAll(arr, p -> p > 10 ? -1 : p);

#### Copying as per the index in array from another array.

       int[] slice = Arrays.copyOfRange(arr, startIndex, endIndex);

#### Printing Array

       Arrays.toString(arr);