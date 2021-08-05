Moyen is a minimalist publishing platform that aims to get out of your way. All of your interactions with Moyen will be made through a **client**. Clients can act on your behalf by means of an **access token**.

Moyen ingests articles written in the [Markdown format](https://en.wikipedia.org/wiki/Markdown) (specifically, [CommonMark](https://commonmark.org)). Not only is Markdown easy to learn, it prevents you from getting locked into the platform using a bespoke file format.

## Step by Step

1. **Create an account**

    [Sign up](/signup) for a free account. If you've previously signed up, [Log in](/login) to your account. You'll need to verify your email address during this step.

1. **Generate an access token**

    Once logged in, [generate an access token](/token) to publish articles via a client. Note that upon creation, an access token is only displayed once; make sure you save it somewhere safe! An access token is like a password and should be kept secret.

1. **Download a client**

    For the time being, there is a single CLI client available. [Install the client](https://github.com/moyen-blog/client-go) by following the linked instructions. Note that the [Go programming language](https://golang.org/) must already be installed on your machine.

1. **Configure your credentials**

    Create a directory that will contain your articles. We'll call this your **workspace**. If you've already got a workspace containing the Markdown documents and images you'd like published, use that. Create a new file in the top level of your workspace with the name *.moyencredentials* (including the leading period). Edit the file so that it appears as follows, replacing the placeholder values with your credentials.

    ```
    username: yourusername
    token: yourtoken
    ```

1. **Publish your articles**

    In the top level of your workspace, run `moyen-cli`. A list of articles to be published will be shown. Type *yes* or *y* to confirm and press enter. After a few seconds, your articles will be published. Visit *yourusername.moyen.blog* to view your published articles.

To see an example workspace, check out the [Moyen documentation](https://github.com/moyen-blog/moyen-documentation). Yes, this is what publishes the very article you're reading right now!

You're all set! Wondering what to do next? See the [Advanced Usage Guide](</Advanced Usage.md>) for some tips and tricks.
