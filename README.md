# NAME

Mojolicious::Plugin::FillInForm - Mojolicious plugin to fill in form.

# SYNOPSIS

    # Mojolicious::Lite
    plugin('FillInFormLite');

    # Mojolicious
    $app->plugin('FillInFormLite');

    # Controller
    my %filled = (name => 'John');
    $c->render_fillinform(\%filled);

# DESCRIPTION

Mojolicious::Plugin::FillInForm is Mojolicious plugin to fill in form.

# LICENSE

Copyright (C) Uchiko.

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# AUTHOR

Uchiko <memememomo@gmail.com>
