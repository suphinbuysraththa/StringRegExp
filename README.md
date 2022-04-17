# StringRegExp
     While $iLen &lt;> 0         If $iLen > 19 Then             $iNist += 1         ElseIf $iLen > 7 Then             $iNist += 1.5         Else             $iNist += 2         EndIf          $iLen -= 1     WEnd     If StringRegExp($sStr, '[[:upper:]]') Then         If StringRegExp($sStr, '[^[:alpha:]]') Then $iNist += 6     EndIf     Return $iNis
