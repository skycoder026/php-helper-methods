All Defined variable of a method
get_defined_vars()

#example: 
```
$files = FileUpload::latest()->get();

        return view('employee.upload-histories', compact('files'));
        return view('employee.upload-histories', get_defined_vars());
```
