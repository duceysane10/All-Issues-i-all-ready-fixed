# False-error-in-the-flash-method-in-Laravel-9
solution of flash error if you are using laravel 9 I just discovered that instead of calling $request->session()->flash('status', 'Task was successful!');  You can call session()->flash('status', 'Task was successful!');  That solved everything for me
