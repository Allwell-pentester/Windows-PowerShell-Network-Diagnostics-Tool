# Windows-PowerShell-Network-Diagnostics-Tool

Windows Network Diagonistics Tool

Windows PowerShell Network Diagnostics Tool

Project Overview

The Windows PowerShell Network Diagnostics Tool is a custom-built network troubleshooting and diagnostics utility developed using PowerShell. The tool combines both active and passive network testing techniques into a single interactive command-line interface designed for Windows environments.


It provides system administrators, IT support personnel, students, and cybersecurity enthusiasts with an all-in-one toolkit for analyzing network connectivity, troubleshooting communication issues, monitoring traffic behavior, and generating diagnostic reports.

Features

Core Network Diagnostic Functions

Display local network configuration

Test network connectivity using ping

Perform traceroute analysis

DNS resolution testing

Network speed testing

Open port scanning

Network latency diagnostics

Wireless network analysis

MTU and packet fragmentation testing

Real-time network monitoring

Full automated diagnostic suite

Export diagnostic reports

Technologies Used

PowerShell

Windows Networking Utilities

TCP/IP Networking

DNS & Routing Analysis

Network Monitoring Techniques

Tool Architecture

The tool operates through a menu-driven interface that allows users to interactively select diagnostic operations.

Main Menu Functions

Option	Function

1	Show local network configuration

2	Test network connectivity

3	Run traceroute

4	Test DNS resolution

5	Test network speed

6	Scan open ports

7	Diagnose network latency

8	Analyze wireless network

9	Test MTU & fragmentation

10	Start real-time network monitor

11	Run complete diagnostics suite

12	Generate/export report

0	Exit

Key Capabilities

1. Network Enumeration

The tool collects detailed information about:

IP addresses

Default gateways

DNS servers

Network adapters

Wireless configurations

2. Connectivity Troubleshooting

Built-in ping and traceroute modules help identify:

Packet loss
Routing issues
Connectivity failures
High latency paths
3. Port Scanning

The application can identify open ports on target hosts to assist with:

Service discovery

Network auditing

Basic security analysis

4. Real-Time Monitoring

Provides live network monitoring capabilities for:

Continuous diagnostics

Active connection observation

Traffic behavior analysis

5. Report Generation

Exports diagnostic results into structured reports for:

Documentation

Incident analysis

Troubleshooting records

Technical presentations

Practical Use Cases

Network troubleshooting

Helpdesk support

Home lab diagnostics

Cybersecurity learning

Network administration practice

IT infrastructure auditing

Educational demonstrations

Project Goals

The objective of this project was to:

Strengthen PowerShell scripting skills

Improve understanding of TCP/IP networking

Automate common troubleshooting tasks

Build a centralized diagnostics toolkit

Gain practical cybersecurity and system administration experience


6

Example Workflow

Launch the PowerShell script as Administrator

Select a diagnostic option from the menu

Run tests against local or remote hosts

Review results in real time

Export findings into a report

Skills Demonstrated

PowerShell scripting

Network diagnostics

TCP/IP analysis

Troubleshooting methodology

Command-line automation

Network monitoring

Basic cybersecurity concepts

System administration

Future Improvements

Planned future enhancements include:

GUI version using Windows Forms or WPF

Advanced vulnerability scanning

Automated threat detection

Logging and alert system

Multi-threaded scanning
Remote device diagnostics
HTML/PDF report generation
Integration with Nmap and Wireshark
