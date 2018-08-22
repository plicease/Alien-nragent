# Alien::nragent [![Build Status](https://secure.travis-ci.org/plicease/Alien-nragent.png)](http://travis-ci.org/plicease/Alien-nragent)

Download and install the NewRelic agent

# SYNOPSIS

    use FFI::Platypus;
    use Alien::nragent;
    
    my $ffi = FFI::Platypus->new;
    $ffi->lib(Alien::nragent->dynamic_libs);
    ...

# DESCRIPTION

This Alien dist installs and makes available the NewRelic agent library.

If the NewRelic agent library is already in your library path, then they will be used.

If the NewRelic agent library is installed in `/opt/newrelic`, then that will be used.

Otherwise the NewRelic agent library will be downloaded, and installed.

# AUTHOR

Graham Ollis <plicease@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2018 by Graham Ollis.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
