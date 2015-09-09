This package contains an example implementation of a voicemail source for
Android.

The source takes care of synchronizing the voicemails stored locally on the
device with the ones stored remotely in a voicemail service. The voicemail
service this application is meant to talk to is based on the OMTP specification
for Visual Voicemail, and comprises of two main components: an IMAP server,
storing the actual voicemails as audio attachments to email messages; and an
SMS server, which sends and receives binary SMS to communicate with the device.

This implementation is neither complete nor production-ready, but it is only a
sample implementation used to provide an example of how the Voicemail related
APIs on Android can be used to integrate a voicemail service.