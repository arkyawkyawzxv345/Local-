# Local-
; Map Memory Leak v3  $Timer = TimerInit() While TimerDiff($Timer) &lt; 10000     For $i = 0 To 5999 Step 1         a()     Next     Sleep(10) WEnd  Func a()     Local $Map[]     $Map.x = 5 EndFunc
