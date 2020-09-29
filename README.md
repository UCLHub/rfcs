# Request for Comments (RFCs) for UCL Hub

**UCL Hub** is an *open-source*, *not-for-profit* student assistant and student
community application.

This repository contains **Request for Changes** (**RFC**) documents. These
documents are intended to guide the design, development and evaluation of
the UCL Hub application, and to serve as a central soruce of reference.

## Creating a New RFC

Fork this repository, then create a new RFC document by copying and filling out
the `rfcs/RFC-0000.md` template RFC.

It is *highly* recommended that you go through an extensive Pre-RFC session to
make sure feedback and design alternatives are properly and thoroughly
considered.

## Request for RFC Review

When you feel that the RFC is sufficiently mature for review, simply ping the
@UCLHub/triage team. A member of the triage team will label your Pull Request
(PR) with suitable labels and ping the suitable team to review your RFC.

## The RFC and FCP Process

The RFC process is specified in [`RFC 0001`](./rfcs/RFC-0001.md).

A member of the selected review team will propose to begin a
**Final Comment Period (FCP)** to either **accept**, **reject** or
**postpone** your RFC. The FCP lasts for 10 calendar days. When a sufficient
number of the teams vote for the FCP decision, the RFC will become **accepted**, 
**rejected** or **postponed**. If there is a lack of sufficient votes, a member
of the selected review team will have to reinitiate the FCP process.

Sometimes RFCs may be *fast-forwarded* if the @UCLHub/core team determines that
it is suitable for fast-fowarding.

If the FCP process successfully terminates and the RFC is **accepted**, then it
will be assigned an **RFC document number** (RFC-DN). This is a unique identifer
that discussions in the relevant UCL Hub repositories and members of the
community can use to refer to the accepted RFC.

## For Maintainers

RFC PRs should be squashed and merged so we maintain a clean and linear
history.
