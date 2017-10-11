# ROLIE

This is a repository to stage ongoing work related to the Resource-oriented Lightweight Information Exchange (ROLIE) draft in the Managed Incident Lightweight Exchange (MILE) working group of the IETF.


## Document Status

The main draft is in IETF Last Call, and can be found under the name draft-ietf-mile-rolie-10.xml.

The secondary CSIRT document spun off of the main document is currently a personal draft targeting the MILE WG, and can be found under the name draft-banghart-mile-rolie-csirt-01.xml. 

An experimental CSS file is being worked on within this Repo for real-time rendering of RFC documents. It can be found under the name rfc7749.css. For now issues may be opened regarding this side project, although if it continues to be a source of discussion it will be moved to a seperate location.

## Contributing

Before submitting feedback, please familiarize yourself with our current issues
list and review the [MILE Working Group](https://datatracker.ietf.org/wg/mile/charter/). If you're
new to this, you may also want to read the [Tao of the
IETF](https://www.ietf.org/tao.html).

Be aware that all contributions to the specification fall under the "NOTE WELL"
terms outlined below.

1. The best way to provide feedback (editorial or design) and ask questions is
sending an e-mail to mile@ietf.org (https://www.ietf.org/mailman/listinfo/MILE). This will ensure that
the entire Working Group sees your input in a timely fashion.

2. If you have **editorial** suggestions (i.e., those that do not change the
meaning of the specification), you can either:

  a) Fork this repository and submit a pull request; this is the lowest
  friction way to get editorial changes in.

  b) Submit a new issue to Github, and mention that you believe it is editorial
  in the issue body. It is not necessary to notify the mailing list for
  editorial issues.  (This is currently the recommended way as the authors are not
  github literate.)

  c) Make comments on individual commits in Github. Note that this feedback is
  processed only with best effort by the editors, so it should only be used for
  quick editorial suggestions or questions.

3. For non-editorial (i.e., **design**) issues, you can also create an issue on
Github. However, you **must notify the mailing list** when creating such issues,
providing a link to the issue in the message body.

  Note that **github issues are not for substantial discussions**; the only
  appropriate place to discuss design issues is on the mailing list itself.


## Building the Draft

The main draft currently compiles using xml2rfc, and the master branch shouldn't produce any major Idnits errors.

The CSS file included can generate a rough estimation of the built draft when applied to the XML. Please note that this building process is NOT officially supported, and does NOT generate an accurate representation. The rendered document is for estimation ONLY. At the moment this CSS file is written in the oXygen Editor CSS subset, this is liable to change.


## NOTE WELL

Any submission to the [IETF](https://www.ietf.org/) intended by the Contributor
for publication as all or part of an IETF Internet-Draft or RFC and any
statement made within the context of an IETF activity is considered an "IETF
Contribution". Such statements include oral statements in IETF sessions, as
well as written and electronic communications made at any time or place, which
are addressed to:

 * The IETF plenary session
 * The IESG, or any member thereof on behalf of the IESG
 * Any IETF mailing list, including the IETF list itself, any working group
   or design team list, or any other list functioning under IETF auspices
 * Any IETF working group or portion thereof
 * Any Birds of a Feather (BOF) session
 * The IAB or any member thereof on behalf of the IAB
 * The RFC Editor or the Internet-Drafts function
 * All IETF Contributions are subject to the rules of
   [RFC 5378](https://tools.ietf.org/html/rfc5378) and
   [RFC 3979](https://tools.ietf.org/html/rfc3979)
   (updated by [RFC 4879](https://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other function,
that are clearly not intended to be input to an IETF activity, group or
function, are not IETF Contributions in the context of this notice.

Please consult [RFC 5378](https://tools.ietf.org/html/rfc5378) and [RFC
3979](https://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules of
process, as documented in Best Current Practices RFCs and IESG Statements.

A participant in any IETF activity acknowledges that written, audio and video
records of meetings may be made and may be available to the public.
