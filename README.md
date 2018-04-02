## _CAOIMHEBot_

_CAOIMHEBot_ is a community response to the growing difficulties of managing
groups relating to adult content on Telegram.

It is primarily intended to help admins of Telegram groups for users aged 18
or over to protect the users of their groups from users under 18 joining those
groups—however well-intentioned they may be—and to protect those users under
18 from people who would seek to exploit or harm them.

### 'Caoimhe'?

_CAOIMHE_ is pronounced "KEE-vuh", is a respected Irish name meaning 'one who
is dear and noble', and stands for Centralised Automated On-line Interlinked
Multi-channel Holistics Endeavour.

What does that mean? It means we really wanted the name to spell out
_CAOIMHE_. :)

### How does it work?

Admins of groups may request that _CAOIMHEBot_ join their group as a member,
and the bot will connect to the group and, for the most part, sit quietly in
the corner and happily ignore almost everything which goes through the groups
to which it has been added.

Nothing is logged, except for commands sent by authorised group admins and
events which _CAOIMHEBot_ itself has triggered, such as kicking or banning a
user or sending a message to a channel or user, or when specific criteria are
met, which are covered below.

Authorised admins of groups to which _CAOIMHEBot_ has been added can add flags
to users, and they can select how those flags are handled in their groups.
Users can not view their own flags, and user flags can only be viewed by the
admin who added the flag and the _CAOIMHEBot_ Management Committee.

When a flag is added to a user, _CAOIMHEBot_ will look for that user in groups
of which it is a member. If it finds that user in one of these groups, it will
check how the particular flag which has been added should be handled for that
group and, if required, execute the necessary actions.

When _CAOIMHEBot_ executes an action on a user, it logs an entry in its
database that the action has been executed. When a flag is removed from a user,
the logs for that flag for that user are deleted and are unrecoverable.
Similarly, if a user account is deleted, _CAOIMHEBot_ will delete its records
associated with that account. Only stub entries will remain to indicate that
a group admin called a command or that _CAOIMHEBot_ performed an action without
indicating the content or target of that command, such as the user to which the
command or action was applied.

### What flags does _CAOIMEBot_ maintain?

Currently, _CAOIMHEBot_ maintains the following flags on users:

<table>
    <thead>
        <tr>
            <th>Flag</th>
            <th>Description</th>
            <th>Default handling</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <code>under-18</code>
            </td>
            <td>
                Indicates that the user is underage and should not be present
                in channels which discuss adult content and legally require a
                minimum age of 18 to join.
            </td>
            <td>
                Kick, ban, and notify admins
            </td>
        </tr>
        <tr>
            <td>
                <code>cp</code>
            </td>
            <td>
                Indicates that the user has posted links to or sought out
                groups or content relating to child pornography or other
                matters.<br/>
                <br/>
                This is a <strong>very</strong> severe flag and must not be
                added to a user without being sure that it is correct.
                Incorrectly flagging a user with this flag will result in
                the admin who added the flag being deauthorised from
                accessing the bot, and possibly also reported to Telegram.
            </td>
            <td>
                Kick, ban, and notify admins<br/>
                <br/>
                This flag can <strong>NOT</strong> be disabled for any
                channels in which <em>CAOIMHEBot</em> is active.
            </td>
        </tr>
    </tbody>
</table>

Flags may be added, modified, or removed, if it becomes necessary to do so.

### Support or Contact

If you:

* have any questions about the operation of CAOIMHEBot;
* wish to be authorised for the bot to join your channel; or
* have had a flag wrongly added to your account and wish to appeal it

please join https://t.me/joinchat/AsxJrE4OglxKnpC8l8zooQ and an admin will help you as soon as possible. This is a non-public channel with message history disabled, so new users will not be able to view old messages, however please do remember that any messages you do send to the channel will be visible to all members currently in the channel.

If you want to discuss your issue privately, please join the channel and say that you have a private matter which you wish to discuss regarding the bot, and a group admin will message you as soon as they are able.

Please **make sure that the user** who contacts you **is actually one of the group's admins**, as users may attempt to impersonate a group admin in order to find out what your query is. If this happens, please say so in the main group and we will aim to resolve the issue as quickly as possible.
