# Log-Analysis-Linux-Command-Line-Profiling
Conducted log profiling using Linux CLI tools (cd, file, cat, head, tail, wc, ls, egrep) to analyze VPN authentication logs and identify suspicious user activity.

Verified file types and log content structure to determine compatibility with SIEM ingestion and manual analysis.

Analyzed time coverage of logs using head and tail to ensure alignment with investigative timeframes.

Counted file lines and checked file size to assess feasibility for manual vs automated analysis.

Performed targeted keyword and IP address searches using egrep to identify successful authentications, user accounts (e.g., “test”), and source IPs (e.g., 88.76.54.33).

Mapped findings to security objectives including detection of unauthorized access and correlating user behavior by IP.

Applied a repeatable analysis framework: define objective → validate log → assess time range → estimate volume → preview content → search effectively.

