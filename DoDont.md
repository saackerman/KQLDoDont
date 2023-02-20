DO | Do's
-----|-----
|Use Time filter first|use Col =~ |
|Use Top 1 instead over board query running tons of data||
|Use filters remove most of data||
|filter early/often befor levarging extend||
|use has instead of contain for performance||
|use specific columns names instead of wildcards when possible||
|for join, use the table with less rows come first||
|for join, project required columns from both sides/tables||

DONT | DONT's
-----|-----

|run query with without a limit| try to be as surgical as possible.||
|filter on calculated column if a table column produces same result||

