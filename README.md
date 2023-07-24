# NAME

Crypt::OpenSSL::ConfiguredAPI - Get the Configured API level if it is defined

# SYNOPSIS

```perl
use Crypt::OpenSSL::ConfiguredAPI;

my $api = Crypt::OpenSSL::ConfiguredAPI->get_configured_api()
```

# DESCRIPTION

Some OpenSSL versions allows you to specify the configured api level.  This
module simply checks whether OPENSSL\_CONFIGURED\_API is defined and returns that
value.

# METHODS

## get\_configured\_api()

Returns the value of the OPENSSL\_CONFIGURED\_API if it is defined or undef if it is undefined

Arguments:

None

# SEE ALSO

Crypt::OpenSSL::Guess allows you to guess the version of openssl installed

# AUTHOR

Timothy Legge, <timlegge@cpan.org>

# COPYRIGHT

Copyright (C) 2023 by Timothy Legge

# LICENSE

Licensed under the Apache License 2.0 (the "License").  You may not use
this file except in compliance with the License.  You can obtain a copy
in the file LICENSE in the source distribution or at
https://www.openssl.org/source/license.html
