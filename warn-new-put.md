This file lists modules PyInstaller was not able to find. This does not
necessarily mean this module is required for running your program. Python and
Python 3rd-party packages include a lot of conditional or optional modules. For
example the module 'ntpath' only exists on Windows, whereas the module
'posixpath' only exists on Posix systems.
Types if import:
* top-level: imported at the top-level - look at these first
* conditional: imported within an if-statement
* delayed: imported within a function
* optional: imported within a try-except-statement
IMPORTANT: Do NOT post this list to the issue-tracker. Use it as a basis for
            tracking down the missing module yourself. Thanks
missing module named pyimod02_importers - imported by D:\Users\A3\AppData\Local\Programs\Python\Python313\Lib\site-packages\PyInstaller\hooks\rthooks\pyi_rth_pkgutil.py (delayed)
missing module named pwd - imported by shutil (delayed, optional), tarfile (optional), pathlib._local (optional), subprocess (delayed, conditional, optional), posixpath (delayed, conditional, optional), netrc (delayed, conditional), getpass (delayed, optional)
missing module named grp - imported by shutil (delayed, optional), tarfile (optional), pathlib._local (optional), subprocess (delayed, conditional, optional)
missing module named posix - imported by shutil (conditional), importlib._bootstrap_external (conditional), os (conditional, optional), posixpath (optional)
missing module named resource - imported by posix (top-level)
missing module named 'collections.abc' - imported by traceback (top-level), inspect (top-level), logging (top-level), typing (top-level), importlib.resources.readers (top-level), selectors (top-level), tracemalloc (top-level), http.client (top-level), typing_extensions (top-level), requests.compat (top-level), socks (optional)
excluded module named _frozen_importlib - imported by importlib (optional), importlib.abc (optional), zipimport (top-level)
missing module named _frozen_importlib_external - imported by importlib._bootstrap (delayed), importlib (optional), importlib.abc (optional), zipimport (top-level)
missing module named _posixsubprocess - imported by subprocess (conditional), multiprocessing.util (delayed)
missing module named fcntl - imported by subprocess (optional)
missing module named _posixshmem - imported by multiprocessing.resource_tracker (conditional), multiprocessing.shared_memory (conditional)
missing module named _scproxy - imported by urllib.request (conditional)
missing module named termios - imported by getpass (optional)
missing module named multiprocessing.BufferTooShort - imported by multiprocessing (top-level), multiprocessing.connection (top-level)
missing module named multiprocessing.AuthenticationError - imported by multiprocessing (top-level), multiprocessing.connection (top-level)
missing module named multiprocessing.get_context - imported by multiprocessing (top-level), multiprocessing.pool (top-level), multiprocessing.managers (top-level), multiprocessing.sharedctypes (top-level)
missing module named multiprocessing.TimeoutError - imported by multiprocessing (top-level), multiprocessing.pool (top-level)
missing module named multiprocessing.set_start_method - imported by multiprocessing (top-level), multiprocessing.spawn (top-level)
missing module named multiprocessing.get_start_method - imported by multiprocessing (top-level), multiprocessing.spawn (top-level)
missing module named _suggestions - imported by traceback (delayed, optional)
missing module named collections.Callable - imported by collections (optional), socks (optional)
missing module named multiprocessing.current_process - imported by multiprocessing (top-level), D:\Python-pj\putnew\new-put.py (top-level)
missing module named multiprocessing.Manager - imported by multiprocessing (top-level), D:\Python-pj\putnew\new-put.py (top-level)
missing module named multiprocessing.Lock - imported by multiprocessing (top-level), D:\Python-pj\putnew\new-put.py (top-level)
missing module named multiprocessing.Pool - imported by multiprocessing (top-level), D:\Python-pj\putnew\new-put.py (top-level)
missing module named simplejson - imported by requests.compat (conditional, optional)
missing module named dummy_threading - imported by requests.cookies (optional)
missing module named 'h2.events' - imported by urllib3.http2.connection (top-level)
missing module named 'h2.connection' - imported by urllib3.http2.connection (top-level)
missing module named h2 - imported by urllib3.http2.connection (top-level)
missing module named zstandard - imported by urllib3.util.request (optional), urllib3.response (optional)
missing module named brotli - imported by urllib3.util.request (optional), urllib3.response (optional)
missing module named brotlicffi - imported by urllib3.util.request (optional), urllib3.response (optional)
missing module named win_inet_pton - imported by socks (conditional, optional)
missing module named cryptography - imported by urllib3.contrib.pyopenssl (top-level), requests (conditional, optional)

![Image](https://github.com/user-attachments/assets/d7419ec9-dc67-403f-bf28-8faea5f1f74f)
missing module named 'OpenSSL.crypto' - imported by urllib3.contrib.pyopenssl (delayed, conditional)
missing module named 'cryptography.x509' - imported by urllib3.contrib.pyopenssl (delayed, optional)
missing module named OpenSSL - imported by urllib3.contrib.pyopenssl (top-level)
missing module named chardet - imported by requests (optional)
missing module named 'pyodide.ffi' - imported by urllib3.contrib.emscripten.fetch (delayed, optional)
missing module named pyodide - imported by urllib3.contrib.emscripten.fetch (top-level)
missing module named js - imported by urllib3.contrib.emscripten.fetch (top-level)
