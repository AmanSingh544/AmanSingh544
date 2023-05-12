- 👋 Hi, I’m @AmanSingh544
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
AmanSingh544/AmanSingh544 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
There must have some edits: the holidays table will be like:

Copy to Clipboard
holidays:
    hld_id
    thl_tp_id
    hld_dt
    hld_cmnt

And the table organizarion should be organization.

Finally my database should be like:

users: //the users of this application. not important in calculations

Copy to Clipboard
*usr_id
usr_fname
usr_lname
usr_uname
usr_pass

organization: //also not important in calculation

Copy to Clipboard
*org_id
org_name
org_address
org_tel
org_web
org_email
org_cat
org_desc

departments: //the highest level of the organization

Copy to Clipboard
*dpt_id(int, ai)
dpt_name(varchar)
dpt_desc

sections: //every department can have several sections

Copy to Clipboard
*sec_id(int, ai)
sec_dpt_id(int) //dpt_id of departments
sec_name(varchar)
sec_desc

designations: //every section can have some designation

Copy to Clipboard
*dsg_id(int, ai)
dsg_sec_id(int) //sec_id of sections
dsg_name
dsg_desc

employee: //every designation can have some employee

Copy to Clipboard
*emp_id(int, ai)
emp_fname(varchar)
emp_lname(varchar)
emp_phone
emp_email
emp_addr
emp_join_dt(date)
emp_salary
emp_card_no
emp_dsg_id(int) //designation of that employee. (dsg_id of designations)
emp_sft_id(int) //sft_id of shifts

shifts: //employees work in shifts

Copy to Clipboard
*sft_id(int, ai)
sft_name(varchar)
sft_from(time) //starting time
sft_to(time) //ending time
sft_desc

leaves: //employees may have leaves

Copy to Clipboard
*lev_id(int, ai)
lev_emp_id(int) //the employee who has taken a leave. (emp_id of employee)
lev_frm(date) //start date
lev_to(date) //end date
lev_desc

holidays:

Copy to Clipboard
*hld_id(int, ai)
hld_tp_id(int) //type of holiday. (hld_tp_id of holiday_types)
hld_dt(date)
hld_cmnt

holiday_types:

Copy to Clipboard
*hld_tp_id(int, ai)
hld_tp_name(varchar)
hld_tp_desc

attendance:

Copy to Clipboard
*att_id(int, ai)
att_emp_id(int) //emp_id of employee
att_time(time)
att_date(date)
att_dir(varchar) //diraction exactly 'In' or 'Out'
![image](https://github.com/AmanSingh544/AmanSingh544/assets/128595290/676c89be-bdb5-40c4-bb91-466348ce694b)

--->
