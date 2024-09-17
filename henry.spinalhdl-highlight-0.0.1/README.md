# SpinalHDL highlight

SpinalHDL highlight uses TextMate to highlight scala files in vscode.

## Bugs

For now, as scala uses "()" instead of "[]" for array access, the highlighter will not work properly with arrays. When arrays are on the right side of an assignment, they will be highlighted as a function call. 

## Notice

This is a modified version of the original scala highlight, where I made some changes focusing on colors, so the names of the matches may not be right. All the changes are accompanied by a comment.

## References

https://github.com/SpinalHDL/SpinalHDL

https://github.com/mads-hartmann/scala.tmbundle

https://github.com/tzyLee/verilog-highlight