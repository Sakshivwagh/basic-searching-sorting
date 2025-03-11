--Insertion Sort

--PSEUDOCODE

BEGIN InsertionSort(arr, n)
    FOR i FROM 1 TO n-1 DO
        key ← arr[i]
        j ← i - 1
        WHILE j >= 0 AND arr[j] > key DO
            arr[j+1] ← arr[j]   
            j ← j - 1
        ENDWHILE
        arr[j+1] ← key  
    ENDFOR
END
