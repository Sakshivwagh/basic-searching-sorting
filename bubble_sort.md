# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
BEGIN BubbleSort(arr, n)
    FOR i FROM 0 TO n-1 DO
        swapped ← false
        FOR j FROM 0 TO n-i-2 DO
            IF arr[j] > arr[j+1] THEN
                SWAP arr[j] and arr[j+1]
                swapped ← true
            ENDIF
        ENDFOR
        IF swapped = false THEN
            BREAK
        ENDIF
    ENDFOR
END

```
