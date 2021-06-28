# This file describes the overall solution intent.

**General requirements

The remote control system is intended initially to allow access to the club&#39;s IC7300 HF transceiver by
club members and other approved users. Other transceivers and other pieces of equipment can be
progressively added. Ideally the first implementation should be complete by the end of July 2021
The system must be accessible by Android and iPhone users, Microsoft PCs and Apple computers
and iPads. Effort should be made to allow operation on legacy operating systems.
The system must be highly secure to prevent access by unauthorised users and by hackers. To
achieve optimum protection a VPN may need to be invoked. The system should not have an annual
licence fee or other cost.
The System should be based on a field proven package that is in wide use and is not an orphan. A
booking system will need to be added to the package.
The system must provide low latency for voice and data and should be able to display waterfalls and
other screen based information. Ideally it should support voice and common data modes such as
WTJSX and similar.
The system must have a remote access back door for system administrators for upgrades,
maintenance, or to take control and shut down the system if necessary.
The remote control system shall include all operator controls for the chosen transceiver and not be
limited to a subset of controls.
or
Alternatively the transceiver setup should be fixed to prevent mal adjustment by inexperienced
operators and functions should be limited to PTT, Band, Frequency and volume
A ten minute time out timer must be incorporated.

**Membership login system.

This should have menu options to access a booking system for remote radios, or to log onto a
current booked time slot.
The login system should interrogate the approved user list of club members.
Username could be their call sign and login should be minimum 7 characters to allow access for F
calls. On joining the initial password would be issued by site administrators after which users would
manage their own secure passwords in accordance with standard security rules.
Members without a call sign would be ineligible to use remote radio options.
The booking system should utilise a readily available calendar system such as Google Calendar or
similar integrated application. It may be necessary to keep the booking system separate from the
login system, ie perhaps on the club website.
The call sign, login and logout times should be electronically recorded. An inactivity timer of say five
minutes should be incorporated to prevent malicious use of the system.

Future possible use of the login system might be management of club records such as Financials,
Membership, Assets, Loans and Fundraising etc. Consideration should be given to possible future
expansion.

**Booking System

A method of booking time slots for use of remote radios. Consider the following:
a) View a calendar to see available time slots and currently booked periods. Viewable for six
months in the future.
b) A method of booking time slots
c) If a time slot is booked, allow that user only to connect to the radio and advise all others that
attempt to use a radio that the system is in use and by whom.
d) Half hour time slots to be allocated for use of a radio with an automatic extension to one hour if
there is no following booking.
e) Only one user at a time should access the system.

**Radio Selection

Initial operation should be confined to the IC7300 to determine popularity of facility by members.
future menu options might be to allow multiple devices with one device in use at a time:

a) IC-7300 or
b) FT-991A or
c) Kiwi SDR, however it may be better to address this separately to allow non licenced members to
access the SDR.
d) If the KiwiSDR is located at the club premises then it needs to be isolated whenever a
transmitting radio option is chosen.

**Restriction of Operation

When a licence is issued to an Amateur they are responsible for adhering to the conditions of their
licence.
A warning could be posted this effect stating that users must adhere to their licence conditions.

Alternatively, the system could manage the licence restrictions for each operator, thus placing more
responsibility on the club.

In this case, on selection of a radio that can transmit, the following control options need to be
considered:
a) The licence class of the user and the limitations imposed there in such as:
i) Transmit power
ii) Frequency bands of operation
iii) Modes of operation

The club membership list contains licence class information which could be used for control of the
above criteria.
a) If it not possible to control these parameters then when the user transmits, power, frequency and
mode should be electronically recorded.
b) Initially antenna selection would be fixed with a single antenna connected to each radio.
c Record electronically who is using each radio and the times of use to determine usage
patterns for committee as an automatic monthly report.
d) A method of powering up/down transmitting radios is required, ie do we need mains power
on/off function or just transceiver on/off

**Antenna Selection

a) Future ability to switch antennas on the transmitting radios. This may require an external
antenna switch unit.
b) Allow control of the beam antenna rotator. Note the same requirement may be required for two
different transceivers
