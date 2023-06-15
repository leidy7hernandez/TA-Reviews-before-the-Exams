# Review before the First Exam. 📚🔍

### Welcome, everyone! Let's dive into the following code together at SUP. We can't wait to see you there! 🎉👩‍💻👨‍💻

### Dataset Download:
https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption

1. Use Pandas to ingest the content of the provided file into a DataFrame object.
This function should report the number of records whose entity is 'Argentina' or 'Australia', returning that value as a tuple (number of Argentina records, number of Australia records).

    Challenge: Create a function that takes a country as a parameter in any case format (Argentina, arGENTina, etc.) and returns the number of records for that country.

2. ExaJulio is a unit different from TWh, meaning it doesn't make sense to add them or find proportions between them. Let's find the formula.

    Create the column "total" that sums all the consumptions. It should be expressed in ExaJulios.

    Challenge: Create a function that takes a country as a parameter in any case format (Argentina, arGENTina, etc.) and returns the sum of 'total' for that country.

3. Create a function that receives three 2-dimensional Numpy arrays and returns a boolean value.

    It should return True if it's possible to perform matrix multiplication between the three matrices (n1 x n2 x n3), and False if it's not possible.

    Example:
    ```python
        n1 = np.array([[0,0,0],[1,1,1],[2,2,2]])
        n2 = np.array([[3,3],[4,4],[5,5]])
        n3 = np.array([1,1],[2,2])

        print(Function(n1,n2,n3))
            True            -> Return value for this example
        print(Function(n2,n1,n3))
            False            -> Return value for this example
    ```

Let's have fun while learning! Good luck with the review! 🚀🌟📝