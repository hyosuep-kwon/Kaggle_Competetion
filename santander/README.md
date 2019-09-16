<div class="competition-data"><div class="sc-frpTsy dIPta"><div class="sc-hEEUtg eikZoe">Data Description</div><div class="sc-fNFDGM biIKCQ"><div class="markdown-converter__text--rendered"><p>In this competition, you are provided with 1.5 years of customers behavior data from Santander bank to predict what new products customers will purchase. The data starts at 2015-01-28 and has monthly records of products a customer has, such as "credit card", "savings account", etc. You will predict what <strong>additional</strong> products a customer will get in the last month, 2016-06-28, in addition to what they already have at 2016-05-28. These products are the columns named:&nbsp;ind_(xyz)_ult1, which are the columns #25 - #48 in the training data. You will predict what a customer will buy <strong>in addition to what they already had at 2016-05-28</strong>.&nbsp;</p>
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
</table></div><div class="sc-hmAwuO dhGSaM"><i sizevalue="18px" class="rmwc-icon google-material-icons sc-dsaGNW iYnmVQ sc-bZQynM gJVwzk">expand_less</i></div></div></div><div class="DataExplorer_Container-sc-3uk7qa koHlGt"><div class="content-box"><div><div class="content-box__title-bar"><div class="ContentBox_Title-sc-6fbrxj iCvEyH" style="line-height: 46px;">Data (237 MB)</div><div class="content-box__right-side"><div class="DataExplorerOverview_TitleBarRight-sc-41u5ex fQnYEh"><div class="DataExplorerOverview_TitleBarItem-sc-7z0gmy jyhbDO"><div><div class="SharedStyles_ApiHintContainer-sc-cgcuc1 ApiHintSmallResponsive_StyledHintCompact-sc-sbnkl4 cKBWdy ApiHintSmallCompact_ApiHintContainer-sc-17duz8y hckICw"><span class="tooltip-multiline SharedStyles_CenteredToolTip-sc-n41yxg enHuzU"><span class="tooltip-multiline__before SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"></span><button class="CopyButton_Button-sc-16vy8q9 cYYUkX"><span name="clipboard" class="SharedStyles_ApiHintIconCopy-sc-1eu1eb5 fzUFsj fa fa-clipboard"></span><span class="ApiHintSmallCompact_ApiHintText-sc-1s9e3xr hHteEJ">API</span></button><span class="tooltip-multiline__after SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"><div class="CodeTooltipContent_Wrapper-sc-lkqmba kwezIx"><div class="CodeTooltipContent_ApiHintTip-sc-1nkilx4 iZUIXd">kaggle competitions download -c santander-product-recommendation</div><div class="CodeTooltipContent_ApiHintTipSub-sc-s0oq66 ntTBf">https://github.com/Kaggle/kaggle-api</div></div></span></span><span class="tooltip-multiline SharedStyles_CenteredToolTip-sc-n41yxg enHuzU"><span class="tooltip-multiline__before SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"></span><a href="https://github.com/Kaggle/kaggle-api" target="_blank" class="HelpLink_A-sc-o61oie rVWiD"><span name="question" class="SharedStyles_ApiHintIconInfo-sc-4hibcj kiRhed fa fa-question"></span></a><span class="tooltip-multiline__after SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"><span>Kaggle API installation and documentation</span></span></span></div><div class="SharedStyles_ApiHintContainer-sc-cgcuc1 ApiHintSmallResponsive_StyledHintDetailed-sc-hd1co6 iTDKiR ApiHintSmallDetailed_Wrapper-sc-a0jdzl ieizJi"><label class="ApiHintSmallDetailed_Label-sc-js3aru cwgHCc">API</label><span class="tooltip-multiline SharedStyles_CenteredToolTip-sc-n41yxg ApiHintSmallDetailed_StyledTooltip-sc-a8eq25 iGVkEw"><span class="tooltip-multiline__before SharedStyles_CenteredToolTip-sc-n41yxg ApiHintSmallDetailed_StyledTooltip-sc-a8eq25 iGVkEw" style="opacity: 0;"></span><button class="ApiHintSmallDetailed_StyledCopyButton-sc-qgini8 eToKDx CopyButton_Button-sc-16vy8q9 cYYUkX"><span name="clipboard" class="SharedStyles_ApiHintIconCopy-sc-1eu1eb5 fzUFsj fa fa-clipboard"></span><div class="ApiHintSmallDetailed_CopyButtonText-sc-q2q09k ithpNd">kaggle competitions download -c santander-product-recommendation</div></button><span class="tooltip-multiline__after SharedStyles_CenteredToolTip-sc-n41yxg ApiHintSmallDetailed_StyledTooltip-sc-a8eq25 iGVkEw" style="opacity: 0;"><div class="CodeTooltipContent_Wrapper-sc-lkqmba kwezIx"><div class="CodeTooltipContent_ApiHintTip-sc-1nkilx4 iZUIXd">kaggle competitions download -c santander-product-recommendation</div><div class="CodeTooltipContent_ApiHintTipSub-sc-s0oq66 ntTBf">https://github.com/Kaggle/kaggle-api</div></div></span></span><span class="tooltip-multiline SharedStyles_CenteredToolTip-sc-n41yxg enHuzU"><span class="tooltip-multiline__before SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"></span><a href="https://github.com/Kaggle/kaggle-api" target="_blank" class="HelpLink_A-sc-o61oie rVWiD"><span name="question" class="SharedStyles_ApiHintIconInfo-sc-4hibcj kiRhed fa fa-question"></span></a><span class="tooltip-multiline__after SharedStyles_CenteredToolTip-sc-n41yxg enHuzU" style="opacity: 0;"><span>Kaggle API installation and documentation</span></span></span></div></div></div><div class="DataExplorerOverview_TitleBarItem-sc-7z0gmy jyhbDO"><a target="_blank" href="/c/5558/download-all" id="comp-data-download-all" class="Data_DownloadAllButton-sc-1hlzqq6 llJnzY"><span name="download" class="Data_DownloadAllIcon-sc-6kn90w kucjil fa fa-download"></span><span class="Data_DownloadAllText-sc-1cqyrcg dubbBf">Download All</span></a></div><div class="DataExplorerOverview_TitleBarItem-sc-7z0gmy jyhbDO"><span name="arrows-alt" class="DataExplorerOverview_ModalButton-sc-16rlqid gECrJu DataExplorerPreview_TitleButtonInactive-sc-bzj2yc dDfMPl fa fa-arrows-alt"></span></div></div></div></div></div><div class="content-box__content-section"><div class="DataExplorerOverview_MainContent-sc-hhkiti hFbgeO"><div class="DataExplorerOverview_Column-sc-1xt9894 DataExplorerOverview_ListColumn-sc-1njtlh9 yQpPz"><div class="DataExplorerList_ExplorerContainer-sc-1a88ctb cTVrfV"><div class="data-explorer-list__header DataExplorerList_Header-sc-kx3nd2 iKHbXp"><div class="DataExplorerList_HeaderTitle-sc-b3zndu eydspt">Data Sources</div><div class="DataExplorerList_HeaderRight-sc-17seut1 gAngP"></div></div><div class="DataExplorerList_Content-sc-t0yrr2 fXPaho"><div class="DataExplorerList_Entry-sc-1uffrzs khXEaG"><div class="DataExplorerList_UnselectedEntry-sc-1lv5br0 DataExplorerList_SelectedEntry-sc-tsuri7 cWTFrR"><div style="width: 16px; min-width: 16px; max-width: 16px;"></div><span name="chevron-right" class="DataExplorerList_CollapsedIcon-sc-1qjwt1i DataExplorerList_DisabledCollapsedIcon-sc-1qkqjxo fZbCWh fa fa-chevron-right"></span><span name="table" class="DataExplorerList_TypeIcon-sc-mjsupj kUeJgO fa fa-table"></span><div class="DataExplorerList_EntryNameToolTip2-sc-kc4oz cMQbPv ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><div data-tip="true" data-for="tooltip_15" class="DataExplorerList_EntryName-sc-12cja4h eKEqwz" currentitem="false">sample_submission.csv</div><div class="__react_component_tooltip place-top type-dark " id="tooltip_15" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY"><span>sample_submission.csv</span></div></div></div><div class="ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><div data-tip="true" data-for="tooltip_16" class="DataExplorerList_EntryInfo-sc-lll5vk gqOAgi" currentitem="false">930k x 2</div><div class="__react_component_tooltip place-top type-dark " id="tooltip_16" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY">930k rows x 2 columns</div></div></div></div></div><div class="DataExplorerList_Entry-sc-1uffrzs khXEaG"><div class="DataExplorerList_UnselectedEntry-sc-1lv5br0 bgskLU"><div style="width: 16px; min-width: 16px; max-width: 16px;"></div><span name="chevron-right" class="DataExplorerList_CollapsedIcon-sc-1qjwt1i DataExplorerList_DisabledCollapsedIcon-sc-1qkqjxo fZbCWh fa fa-chevron-right"></span><span name="table" class="DataExplorerList_TypeIcon-sc-mjsupj kUeJgO fa fa-table"></span><div class="DataExplorerList_EntryNameToolTip2-sc-kc4oz cMQbPv ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><div data-tip="true" data-for="tooltip_17" class="DataExplorerList_EntryName-sc-12cja4h eKEqwz" currentitem="false">test_ver2.csv</div><div class="__react_component_tooltip place-top type-dark " id="tooltip_17" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY"><span>test_ver2.csv</span></div></div></div><div class="ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><div data-tip="true" data-for="tooltip_18" class="DataExplorerList_EntryInfo-sc-lll5vk gqOAgi" currentitem="false">930k x 24</div><div class="__react_component_tooltip place-top type-dark " id="tooltip_18" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY">930k rows x 24 columns</div></div></div></div></div><div class="DataExplorerList_Entry-sc-1uffrzs khXEaG"><div class="DataExplorerList_UnselectedEntry-sc-1lv5br0 bgskLU"><div style="width: 16px; min-width: 16px; max-width: 16px;"></div><span name="chevron-right" class="DataExplorerList_CollapsedIcon-sc-1qjwt1i DataExplorerList_DisabledCollapsedIcon-sc-1qkqjxo fZbCWh fa fa-chevron-right"></span><span name="table" class="DataExplorerList_TypeIcon-sc-mjsupj kUeJgO fa fa-table"></span><div class="DataExplorerList_EntryNameToolTip2-sc-kc4oz cMQbPv ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><div data-tip="true" data-for="tooltip_19" class="DataExplorerList_EntryName-sc-12cja4h eKEqwz" currentitem="false">train_ver2.csv</div><div class="__react_component_tooltip place-top type-dark " id="tooltip_19" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY"><span>train_ver2.csv</span></div></div></div><div class="DataExplorerList_EntryInfoSpacer-sc-6qxfsx Hmlgy"></div></div></div></div></div></div><div class="DataExplorerOverview_Column-sc-1xt9894 DataExplorerOverview_ObjectColumn-sc-v8kz4s ihDqUe"><div class="DataExplorerDescription_Container-sc-rtvgew bNXSrs"><div class="DataExplorerDescription_Header-sc-9udzgu kagSZQ"><div class="DataExplorerDescription_HeaderTitle-sc-8yzcy8 kIiVNS">About this file</div><div class="DataExplorerDescription_HeaderRight-sc-m2iwyg fyjBEU"></div></div><div class="DataExplorerDescription_Content-sc-yp9anb eysdMp"><div class="markdown-converter__text--rendered data-explorer-overview-description"><p>No description yet</p></div></div></div></div><div class="DataExplorerOverview_Column-sc-1xt9894 DataExplorerOverview_ColumnColumn-sc-11h9ytg liCEVK"><div class="DataExplorerColumns_Container-sc-1464fds ezQBOi"><div class="DataExplorerColumns_Header-sc-118cn9q cFMdJU"><div class="DataExplorerColumns_HeaderTitle-sc-kxsg96 iycOVv">Columns</div><div class="DataExplorerColumns_HeaderRight-sc-19xkcvh gBIOpQ"></div></div><div class="DataExplorerColumns_Content-sc-nd4frg jtcGRH"><div class="DataExplorerColumns_Column-sc-3o3eue dzfjqf"><div class="DataExplorerColumns_ColumnType-sc-1ro23id bXvfMT"><div class="ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><span name="hashtag" data-tip="true" data-for="tooltip_20" class="DataExplorerColumns_ColumnTypeIcon-sc-17opb71 bLaitT fa fa-hashtag" currentitem="false"></span><div class="__react_component_tooltip place-top type-dark " id="tooltip_20" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY">Numeric</div></div></div></div><div class="DataExplorerColumns_ColumnMain-sc-sx1t3y kHFuWO"><span class="DataExplorerColumns_ColumnName-sc-1tzfrn7 fqEMUL">ncodpers</span></div></div><div class="DataExplorerColumns_Column-sc-3o3eue dzfjqf"><div class="DataExplorerColumns_ColumnType-sc-1ro23id bXvfMT"><div class="ToolTip_ToolTipContainer-sc-f0vhmk eHUYTV"><span name="font" data-tip="true" data-for="tooltip_21" class="DataExplorerColumns_ColumnTypeIcon-sc-17opb71 bLaitT fa fa-font" currentitem="false"></span><div class="__react_component_tooltip place-top type-dark " id="tooltip_21" data-id="tooltip"><div class="ToolTip_ToolTipView-sc-1ci7zcv iiWQyY">String</div></div></div></div><div class="DataExplorerColumns_ColumnMain-sc-sx1t3y kHFuWO"><span class="DataExplorerColumns_ColumnName-sc-1tzfrn7 fqEMUL">added_products</span></div></div></div></div></div></div></div></div></div></div>
