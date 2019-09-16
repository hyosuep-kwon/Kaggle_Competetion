<div class="competition-data"><div class="sc-frpTsy dIPta"><div class="sc-hEEUtg eikZoe"><h2>Data Description</h2></div><div class="sc-fNFDGM biIKCQ"><div class="markdown-converter__text--rendered"><p>In this competition, you are provided with 1.5 years of customers behavior data from Santander bank to predict what new products customers will purchase. The data starts at 2015-01-28 and has monthly records of products a customer has, such as "credit card", "savings account", etc. You will predict what <strong>additional</strong> products a customer will get in the last month, 2016-06-28, in addition to what they already have at 2016-05-28. These products are the columns named:&nbsp;ind_(xyz)_ult1, which are the columns #25 - #48 in the training data. You will predict what a customer will buy <strong>in addition to what they already had at 2016-05-28</strong>.&nbsp;</p>
<p>The test and train sets are split by time, and public and private leaderboard sets are split randomly.</p>
<p><strong>Please note:&nbsp;This sample does not include any real Santander Spain customers, and thus it is not representative of Spain's customer base.&nbsp;</strong></p>
<h2>File descriptions</h2>
<ul>
<li><strong>train.csv</strong> - the training set</li>
<li><strong>test.csv</strong> - the test set</li>
<li><strong>sample_submission.csv</strong> - a sample submission file in the correct format</li>
</ul>
<h2>Data fields</h2>
<table>
<thead>
<tr><th>Column Name</th><th>Description</th></tr>
</thead>
<tbody>
<tr>
<td>fecha_dato</td>
<td>The table is partitioned for this column</td>
</tr>
<tr>
<td>ncodpers</td>
<td>Customer code</td>
</tr>
<tr>
<td>ind_empleado</td>
<td>Employee index: A active, B ex employed, F filial, N not employee, P pasive</td>
</tr>
<tr>
<td>pais_residencia</td>
<td>Customer's Country residence</td>
</tr>
<tr>
<td>sexo</td>
<td>Customer's sex</td>
</tr>
<tr>
<td>age</td>
<td>Age</td>
</tr>
<tr>
<td>fecha_alta</td>
<td>The date in which the customer became as the first holder of a contract in the bank</td>
</tr>
<tr>
<td>ind_nuevo</td>
<td>New customer Index. 1 if the customer registered in the last 6 months.</td>
</tr>
<tr>
<td>antiguedad</td>
<td>Customer seniority (in months)</td>
</tr>
<tr>
<td>indrel</td>
<td>1 (First/Primary), 99 (Primary customer during the month but not at the end of the month)</td>
</tr>
<tr>
<td>ult_fec_cli_1t</td>
<td>Last date as primary customer (if he isn't at the end of the month)</td>
</tr>
<tr>
<td>indrel_1mes</td>
<td>Customer type at the beginning of the month ,1 (First/Primary customer), 2 (co-owner ),P (Potential),3 (former primary), 4(former co-owner)</td>
</tr>
<tr>
<td>tiprel_1mes</td>
<td>Customer relation type at the beginning of the month, A (active), I (inactive), P (former customer),R (Potential)</td>
</tr>
<tr>
<td>indresi</td>
<td>Residence index (S (Yes) or N (No) if the residence country is the same than the bank country)</td>
</tr>
<tr>
<td>indext</td>
<td>Foreigner index (S (Yes) or N (No) if the customer's birth country is different than the bank country)</td>
</tr>
<tr>
<td>conyuemp</td>
<td>Spouse index. 1 if the customer is spouse of an employee</td>
</tr>
<tr>
<td>canal_entrada</td>
<td>channel used by the customer to join</td>
</tr>
<tr>
<td>indfall</td>
<td>Deceased index. N/S</td>
</tr>
<tr>
<td>tipodom</td>
<td>Addres type. 1, primary address</td>
</tr>
<tr>
<td>cod_prov</td>
<td>Province code (customer's address)</td>
</tr>
<tr>
<td>nomprov</td>
<td>Province name</td>
</tr>
<tr>
<td>ind_actividad_cliente</td>
<td>Activity index (1, active customer; 0, inactive customer)</td>
</tr>
<tr>
<td>renta</td>
<td>Gross income of the household</td>
</tr>
<tr>
<td>segmento</td>
<td>segmentation: 01 - VIP, 02 - Individuals 03 - college graduated</td>
</tr>
<tr>
<td>ind_ahor_fin_ult1</td>
<td>Saving Account</td>
</tr>
<tr>
<td>ind_aval_fin_ult1</td>
<td>Guarantees</td>
</tr>
<tr>
<td>ind_cco_fin_ult1</td>
<td>Current Accounts</td>
</tr>
<tr>
<td>ind_cder_fin_ult1</td>
<td>Derivada Account</td>
</tr>
<tr>
<td>ind_cno_fin_ult1</td>
<td>Payroll Account</td>
</tr>
<tr>
<td>ind_ctju_fin_ult1</td>
<td>Junior Account</td>
</tr>
<tr>
<td>ind_ctma_fin_ult1</td>
<td>Más particular Account</td>
</tr>
<tr>
<td>ind_ctop_fin_ult1</td>
<td>particular Account</td>
</tr>
<tr>
<td>ind_ctpp_fin_ult1</td>
<td>particular Plus Account</td>
</tr>
<tr>
<td>ind_deco_fin_ult1</td>
<td>Short-term deposits</td>
</tr>
<tr>
<td>ind_deme_fin_ult1</td>
<td>Medium-term deposits</td>
</tr>
<tr>
<td>ind_dela_fin_ult1</td>
<td>Long-term deposits</td>
</tr>
<tr>
<td>ind_ecue_fin_ult1</td>
<td>e-account</td>
</tr>
<tr>
<td>ind_fond_fin_ult1</td>
<td>Funds</td>
</tr>
<tr>
<td>ind_hip_fin_ult1</td>
<td>Mortgage</td>
</tr>
<tr>
<td>ind_plan_fin_ult1</td>
<td>Pensions</td>
</tr>
<tr>
<td>ind_pres_fin_ult1</td>
<td>Loans</td>
</tr>
<tr>
<td>ind_reca_fin_ult1</td>
<td>Taxes</td>
</tr>
<tr>
<td>ind_tjcr_fin_ult1</td>
<td>Credit Card</td>
</tr>
<tr>
<td>ind_valo_fin_ult1</td>
<td>Securities</td>
</tr>
<tr>
<td>ind_viv_fin_ult1</td>
<td>Home Account</td>
</tr>
<tr>
<td>ind_nomina_ult1</td>
<td>Payroll</td>
</tr>
<tr>
<td>ind_nom_pens_ult1</td>
<td>Pensions</td>
</tr>
<tr>
<td>ind_recibo_ult1</td>
<td>Direct Debit</td>
</tr>
</tbody>
</table></div>
