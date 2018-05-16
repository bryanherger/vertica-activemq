# vertica-activemq

This Java project shows the basic components to consume from ActiveMQ and push to Vertica.
The project uses Apache ActiveMQ and c3p0 connection pooling.

This is an IntelliJ Maven project.  It should compile with targets "clean package assembly:single"

You'll need to review and customize to match your message format and table schema.
You can specify a fair amount of configuration dynamically using a Properties object,
but you'll have to edit the code to convert a Message to a SQL INSERT in VerticaSink.java