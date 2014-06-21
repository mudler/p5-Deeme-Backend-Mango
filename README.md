# NAME

Deeme::Backend::Mango - MongoDB Backend using Mango for Deeme

# SYNOPSIS

    use Deeme::Backend::Mango;
    my $e = Deeme->new( backend => Deeme::Backend::Mango->new(
          database => "deeme",
          host     => "mongodb://user:pass@localhost:27017",
      ) );

# DESCRIPTION

Deeme::Backend::Mango is a MongoDB Deeme memory backend using Mango.

# AUTHOR

mudler <mudler@dark-lab.net>

# COPYRIGHT

Copyright 2014- mudler

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Deeme](https://metacpan.org/pod/Deeme)
