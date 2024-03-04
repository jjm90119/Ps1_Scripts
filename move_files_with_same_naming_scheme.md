$sourcepath = "C:\path\to\folder\"
$destinationpath = "C:\path\to\folder\"
$filepatterns = @("name*", "name2*")
copy-item -path "$sourcepath\*" -destination $destinationpath -recurse -force -include $filepatterns
