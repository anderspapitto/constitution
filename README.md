# Constitution

## Preamble

This constitution is established with the aims of respecting human rights,
preserving invidual liberty, embodying democracy and the rule of law, promoting
the general welfare, and ensuring the good faith of the government in acting in
the public interest.

## Structure of Government and Division of Powers

The powers of government are divided between five branches of government. These
are
  - legislative
  - judicial
  - military
  - executive
  - integrity

## The Legislative Branch
- The legislature is a unicameral body known as the Senate.
- Several Consuls are further drawn from the ranks of the Senate.
- Consuls introduce legislation and nominates candidates for government offices.
- The full Senate votes on legislation and candidates introduced by the Consuls.

### Composition and Election

#### Senate
- The Senate is composed of 99 members, who serve for five year terms.
- Members are chosen by [Closed Party List Proportional
  Representation](https://en.wikipedia.org/wiki/Party-list_proportional_representation).
- When a member of the legislature leaves office prematurely (e.g. dies,
  resigns), the party which they were elected as a member of chooses a
  replacement.

#### Consuls
- There are five Consuls, who serve for six month terms.
- Consuls are elected by the Senate from within their own ranks via [Single
  Transferrable Vote](https://en.wikipedia.org/wiki/Single_transferable_vote).

#### Commentary on [Composition and Election](#composition-and-election)
- The Senate is intended to represent the voting population accurately, while
  significantly reducing cardinality and being extremely simple for the voting
  population to elect.
- Decisions made by the Senate can be subject to more complicated rules
  that have other desirable properties (e.g. favoring consensus options),
  because they are being made by few specialists rather than many
  non-specialists.
- Consuls unavoidably have more power/influence. To limit the accumulation of
  power, their terms are significantly limited, which is not a problem because
  they require only a lightweight vote in the Senate, rather than a full
  election by the general public. 
- Note that there is no location-based representation in the Senate.
- Note that 99 members of the Senate implies that a X% vote threshold
  requires exactly X votes (e.g. 50 votes for simple majority). This is a bit of
  a gimmick.

### Powers
- The Senate has the exclusive power to pass legislation (subject to
  judicial review).
- The Senate has the exclusive power to make appointments to the other
  branches of government.
- The Senate has the power to determine through legislation the structure and
  staffing of each branch of government, in a manner consistent with what is
  explicitly described in this Constitution.
  
#### Appointments
- For each position to be filled, each Consul may nominate one candidate.
- The selection is determined by Approval Voting of the full Senate.
- The full Senate may hold a vote of no confidence in any Senate-appointed
  official other than those in the judicial and integrity branches, introduced
  by any Consul and with a simple majority threshold.
- If successful, the Senate appoints a replacement as if filling an empty
  position, except that the current office-holder is added to the list of
  candidates and receives 10 bonus votes.

##### Commentary on [Appointments](#appointments)
- Approval voting favors consensus candidates. The motivation is that the
  mechanism for the voting population to affect the partisan makeup of the
  government is via election to the legislature. Appointments to other branches
  should not compound majority influence, e.g. as would happen with FPTP voting.
- Five Consuls are used as a streamlined approximation of allowing each
  member of the Senate to introduce a nominee for each position. Because
  Consuls are chosen from the Senate via a proportional voting system,
  there should be minimal distortion relative to direct election of Consuls
  from voting population.
- Note that appointments are relatively accountable and direct to the voting
  population, because although nominations are three indirections away (voting
  population -> Senate -> Consuls -> nominee), the actual selection is
  only two (voting population -> Senate -> nominee)
- The mechanism for replacing existing appointments is meant to allow
  replacement of misaligned or low-performing officials, while being resistant
  to excess churn.

#### Passing Legislation
- Consuls are exclusively empowered to introduce legislation for
  consideration.
- Legislation and other acts of the Senate have varying vote thresholds,
  depending on content, as arbitrated by the Judiciary.
- Voting thresholds are with respect to the full size of the Senate.
  Missing members, abstained votes, etc., count as No votes.

- Legislation which restricts or penalizes freedom and actions require
  supermajorities according to the following scheme.

|                | Natural Person | Business / Non-natural person |
|----------------|----------------|-------------------------------|
| Non-commercial | 90%            | 80%                           |
| Commercial     | 70%            | 60%                           |

- Budget legislation requires a simple majority.

- Declarations of war require an 80% supermajority.

- Amendments to the consistution require a 70% supermajority.

- Amendments to the consistution which have the effect of reducing or increasing
  the required supermajority threshold for any purpose require a supermajority
  equal to the larger of the old and new threshold, plus an additional 10
  percentage points.

- All legislation which requires a supermajority may instead be passed at a
  lower vote threshold, if it is passed by each of two successive Senates,
  at least 3 years apart. In such cases the vote threshold is 10 percentage
  points lower than for immediate passage (but not to be reduced below simple
  majority).
  
##### Repudiating Legislation
- Legislation which required a supermajority to enact may be repealed if it does
  not maintain supermajority support.
- Repeals may be introduced by Consuls, as with other legislation.
- Repealing an act which required N% votes to enact requires (110 - N)% votes to
  repeal (not to exceed a requirement of simple majority).
- Repeals, like enactment of legislation, may occur with a lower vote threshold
  if passed by each of two successive Senates, at least 3 years apart. The
  vote threshold is likewise reduced by 10 percentage points .

##### Commentary on [Passing Legislation](#passing-legislation)
- The intent is to have a clear and hard-to-game distinction between different
  types of legislation.
- This allows the most benign and basic operations of government which have
  broad consensus to be freed from political gridlock, while adding hurdles to
  the type of legislation that carries risks of persecution and power grabs.
- Note there is no executive veto.

## Military

### Composition and Appointment
- The military is under the control of the Council of Defense, composed of five
  members.
- Members are not co-equal, but are appointed to five separate posts, which are
  ranked.
- The ranking member of the Council of Defense at any moment acts as the
  Secretary of Defense.
- Members of the Council of Defense are appointed by the Senate as described
  above.
- Members are appointed for one year terms.
- No one may serve in the Council of Defense for more than ten years in their
  lifetime.

#### Restrictions on Combining Military and Civilian Authority
- High-ranking military officers ([General
  Officers](https://en.wikipedia.org/wiki/General_officer) according to the NATO
  definition) are barred from holding any national political office for the rest
  of their lives.
- For this purpose the Council of Defense counts as both a high-ranking military
  office, and as a political office. Therefore high ranking military officers
  may not be appointed to the Council of Defense, and anyone who is appointed to
  the Council of Defense may never again hold other national political office.
  
### Powers
- The Secretary of Defense has sole authority over the military.

### Commentary on [Military](#military)
- It is a primary concern of this constitution to limit the possibility of
  military takeover of government. To that end, the military is always under
  civilian control, and no individual should hold both military and civilian
  government authority.
- The military in particular needs a clear line of succession, due to the risks
  of the Secretary of Defense being killed or otherwise leaving office during
  wartime.

## Judiciary

### Composition and Appointment
- The highest court is a 9 member Supreme Court.
- Members of the Supreme Court and other national courts are appointed by the
  Senate as described above.
- Appointments are for 9 year terms.
- Appointments to the Supreme Court are staggered, one year apart.
- In case of vacancy on Supreme Court, the appointed replacement serves out the
  remainder of the term, in order to keep the staggered terms in sync.
- Members of the judiciary may not be removed by the Senate after appointment.

### Powers
- The Supreme Court has the power to determine whether legislation is valid
  under this Constitution.
- The Supreme Court has the power to determine which voting threshold applies to
  a given piece of legislation.

### Miscellaneous
- When any entity makes a payment to counsel in the course of a judicial or
  administrative proceeding, one fifth of that payment is due to opposing
  counsel. In the case of litigation with more than two parties, the court will
  determine the relative apportionment of these funds. This includes cases where
  the government is one of the parties.
- Nondisclosure agreements are unenforceable, except in the case of trade
  secrets.

#### Commentary on [Miscellaneous](#miscellaneous)
- It is in the public interest to mitigate the effect of unequal resources and
  counsel with regard to litigation. 

## Executive

### Composition and Appointment
- The head of each department is appointed by the Senate as described above.

### Powers
- The executive carries out the laws passed by the Senate.

### Commentary on [Executive](#civilian-executive)
- Note that there is no single executive leader.

## Integrity

The Integrity branch is a limited-purpose independent judicial system intended
to police corruption by government officials.

### Composition and Appointment
- The Integrity branch consists of the Integrity Court System, a court subbranch, and
  the Integrity Investigatory Agency, an investigatory and prosecutorial subbranch.
- Members of the Integrity branch may not be removed by the Senate after appointment.

#### Integrity Court System
- The highest authorities in the Integrity Court System are three symmetric and
  coequal courts, named Integrity High Court A, Integrity High Court B, and
  Integrity High Court C.
- Each Integrity High Court has 9 members.
- Members are appointed by the Senate as described above.
- Appointments are for 9 year terms, staggered one year apart.

#### Integrity Investigatory Agency
- The highest authorities in the Integrity Investigatory Agency are three
  coequal Integrity Attorneys General.
- Integrity Attorneys General are appointed by the Senate for 6 year terms,
  staggered 2 years apart.

### Powers

#### Integrity Investigatory Agency
- Any Integrity Attorney General may, independently or in concert with one
  another, open investigations and prosecute cases before the Integrity Courts.
- The Integrity Investigatory Agency may institute programs for collection of
  information on, and requirements for documentation from, government officials
  when it serves the purposes of preventing, detecting, and prosecuting
  corruption by government officials.
- Whether such information collection and documentation requirements serve a
  valid purpose may be challenged before the Judiciary.

#### Integrity Court System
- Hears cases brought by the Integrity Investigatory Agency
- When the target of an investigation is themselves a member of one of the
  Integrity High Courts, the case is heard by the next High Court in the cycle.
- Otherwise, one of the High Courts is randomly assigned.
- May remove individuals from office and/or bar them from future office-holding.
- May require individuals to divest from conflicted financial interests as a
  condition of office-holding.

### Commentary on [Integrity](#integrity)
- Limiting and addressing corruption within the government is a first-class
  concern. The intent is to remove individual bad actors, with minimal influence
  on policy and balance of power between parties.
- There is a tension between structure/complexity, which can be useful to guard
  against well-known and common pitfalls, and simplicity, which can be useful to
  increase public trust and guard against unintended consequences.
- The guiding principle is that one one should be their own judge. This is taken
  one step further to say that there should be no cycle of two entities, each of
  which is the other's judge. It could be taken even further (more than 3 High
  Courts), but this has diminishing returns and an increase in complexity.

## Human Rights
- Right to effective legal representation, as described above.
- Rights of children take precendence over rights of parents.
- Plus standard rights e.g. taken from US constitution.
