--Selection Sort

---PSEUDOCODE

BEGIN SelectionSort(arr, n)
    FOR i FROM 0 TO n-2 DO
        minIndex ← i
        FOR j FROM i+1 TO n-1 DO
            IF arr[j] < arr[minIndex] THEN
                minIndex ← j
            ENDIF
        ENDFOR
        SWAP arr[i] and arr[minIndex]
    ENDFOR
END
