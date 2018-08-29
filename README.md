# Project
<htmlform>
    <style>
        .section {
            border: 1px solid $ headerColor;
            padding: 2px;
            text-align: left;
            margin-bottom: 1em;
        }

        .sectionHeader {
            background-color:pink;
            color: $ fontOnHeaderColor;
            display: block;
            padding: 2px;
            font-weight: bold;
        }

        table.baseline-aligned td {
            vertical-align: baseline;
        }

        @media print {
            .printable {
                background-color: white;
                height: 100%;
                width: 100%;
                position: fixed;
                top: 0;
                left: 0;
                margin: 0;
                padding: 15px;
                font-size: 14px;
                line-height: 18px;
            }
        }
    </style>


    <script language="javascript">
        jQuery(function () {

            jQuery('#w8').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/4afa3435-6fb7-4163-af3a-9f1e6cab120c",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w8_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w8_text').remove();
                }
            });

            jQuery('#w10').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/594d4048-6926-4883-a615-f5ab8e71334e",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w10_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w10_text').remove();
                }
            });
           jQuery('#w12').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/cf2eb62d-2196-4a9a-9447-8bae9fb4ff4a",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w12_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w10_text').remove();
                }
            });
 jQuery('#w14').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/17340ccf-15f3-4e7b-8ae7-b94c77619662",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w14_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w14_text').remove();
                }
            });
 jQuery('#w16').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/c2f761db-8dc3-41d1-a911-75df8ba24d28",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w16_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w16_text').remove();
                }
            });

jQuery('#w18').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/a5e760fa-ab21-4d6d-9f22-4e70b54ff258",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w18_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w18_text').remove();
                }
            });
jQuery('#w20').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/8cd5cb4e-ca50-4665-b2eb-07e8e1ed6802",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w20_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w20_text').remove();
                }
            });
jQuery('#w22').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/b3993c57-02db-463d-9ad0-688fd6a7ddd6",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w22_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w22_text').remove();
                }
            });
jQuery('#w24').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/ebc4c1b4-da5a-4c47-9fd4-8143c668035c",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w24_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w24_text').remove();
                }
            });
jQuery('#w26').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/646b02e7-4683-4bed-883d-9c204e1dc85d",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w26_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w26_text').remove();
                }
            });
jQuery('#w28').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/3c5a8cea-4fa7-444f-a68f-66a83cc336d2",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w28_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w28_text').remove();
                }
            });
jQuery('#w30').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/17169c39-6b99-4858-841d-58e0c5e6a439",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w30_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w30_text').remove();
                }
            });
jQuery('#w32').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/baf52012-d938-4ce0-90b9-9bbfc04b161a",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w32_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w32_text').remove();
                }
            });
jQuery('#w34').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/	45d84479-aa27-42da-bf01-a98476b73853",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w34_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w34_text').remove();
                }
            });
jQuery('#w40').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/a5e760fa-ab21-4d6d-9f22-4e70b54ff258",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w40_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w40_text').remove();
                }
            });
jQuery('#w42').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/dbb36e17-f1ff-4991-9549-9ba4aa419891",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w42_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w42_text').remove();
                }
            });
jQuery('#w44').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/57472995-fb1f-4e4e-980b-ebe6440b8bd7",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w44_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w44_text').remove();
                }
            });
jQuery('#w46').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/14a2b38f-0342-4c6e-8eaa-c5f623ebebfe",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w46_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w46_text').remove();
                }
            });
jQuery('#w48').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/ac6ea0c9-7dab-47a2-93f9-07682d2d5827",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w48_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w48_text').remove();
                }
            });
jQuery('#w50').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/fcbb637a-6532-4d99-a52b-9f8f29cdecce",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w50_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w50_text').remove();
                }
            });
jQuery('#w52').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/c088b488-1eea-4ef7-86a2-4029de8b8aca",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w52_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w52_text').remove();
                }
            });
jQuery('#w54').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/758b3a60-bc5c-4c14-aec8-17a64d56bb5b",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w54_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w54_text').remove();
                }
            });
jQuery('#w56').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/59990460-2ed6-4501-bec8-557a1401112a",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w56_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w56_text').remove();
                }
            });
jQuery('#w58').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/b84a26a3-68c7-45e9-a9ed-03e9b7a5a309",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w58_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w58_text').remove();
                }
            });
jQuery('#w60').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/1b687784-ac89-42d0-bd62-88ec8c83dc48",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w60_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w60_text').remove();
                }
            });
jQuery('#w62').change(function () {
                if (jQuery(this).is(":checked")) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/4ab01851-c2d3-4f80-905c-faec5b5be120",
                        function (json) {
                            jQuery('#stageDialog').append('<span id="w62_text">' + json.descriptions[0].display + '</span>');
                        });
                } else {
                    jQuery('#w62_text').remove();
                }
            });
            getField('patientstage.value').change(function () {
                if (getValue('patientstage.value') == 6184) {
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/0b3dd811-8f82-47cc-b1ca-49ed30e5d515",
                        function (json) {
                            jQuery('#stage_text').remove();
                            jQuery('#stageDialog').append('<span id="stage_text">' + json.descriptions[0].display + '</span>');
                        });
                    jQuery('#stageDiv').removeAttr('style').show();
                }
                else if (getValue('patientstage.value') == 6186) {
                    jQuery('#stageDiv').removeAttr('style').show();
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/ebedea79-ce0a-412e-ab12-9debe36a0e08",
                        function (json) {
                            jQuery('#stage_text').remove();
                            jQuery('#stageDialog').append('<span id="stage_text">' + json.descriptions[0].display + '</span>');
                        });
                }
                else if (getValue('patientstage.value') == 6187) {
                    jQuery('#stageDiv').removeAttr('style').show();
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/b17d7752-9904-4e60-a581-11b42d1c91d2",
                        function (json) {
                            jQuery('#stage_text').remove();
                            jQuery('#stageDialog').append('<span id="stage_text">' + json.descriptions[0].display + '</span>');
                        });
                }
                else if (getValue('patientstage.value') == 6188) {
                    jQuery('#stageDiv').removeAttr('style').show();
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/1de0e99a-0bd8-4da5-b619-a1d45caee152",
                        function (json) {
                            jQuery('#stage_text').remove();
                            jQuery('#stageDialog').append('<span id="stage_text">' + json.descriptions[0].display + '</span>');
                        });
                }
                else if (getValue('patientstage.value') == 6185) {
                    jQuery('#stageDiv').removeAttr('style').show();
                    jQuery.getJSON("https://in-info-web7.informatics.iupui.edu/openmrs/ws/rest/v1/concept/914e852d-a513-4dae-be13-e12025ef4b5f",
                        function (json) {
                            jQuery('#stage_text').remove();
                            jQuery('#stageDialog').append('<span id="stage_text">' + json.descriptions[0].display + '</span>');
                        });
                }
                else {
                    jQuery('#stage_text').remove();
                    jQuery('#stageDiv').removeAttr('style').hide();
                }
            });
        });

        function showStageInfo() {
            jQuery("#dialog").dialog({width: 800});
        }
    </script>

    <h2>Breast cancer(v1)</h2>

    <section headerLabel="1. Encounter Details">
        <table class="baseline-aligned">
            <tr>
                <td>Date:</td>
                <td>
                    <encounterDate default="today"/>
                </td>
            </tr>
            <tr>
                <td>Location:</td>
                <td>
                    <encounterLocation/>
                </td>
            </tr>
            <tr>
                <td>Provider:</td>
                <td>
                    <encounterProvider/>
                </td>
            </tr>
        </table>
    </section>

    <section headerLabel="2. Current Breast Problem ">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6222" labelText="Mass or Lump" id="mlinfo" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>	
                    <obs conceptId="6224" labelText="Nipple Discharge" id="ndinfo" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6227" labelText="Abnormal Mammogram" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6230" labelText="Breast Pain" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6232" labelText="No Current Breast Problems" style="checkbox"/>
                </td>
            </tr>
        </table>
    </section>
    <!--||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||-->
    <section headerLabel="3. Past breast history">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6285" labelText="Breast cancer" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6223" labelText="Breast cyst" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6225" labelText="Breast biopsy" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6226" labelText="Other past breast history" style="checkbox"/>
                </td>
            </tr>
        </table>
    </section>
    <section headerLabel="4. Other imaging history">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6178" labelText="Breast Ultrasound" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6180" labelText="Breast MRI" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6181" labelText="Breast CT" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6183" labelText="Bone Scan" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6182" labelText="PET" style="checkbox"/>
                </td>
            </tr>
        </table>
    </section>
    <section headerLabel="5. MAMMOGRAM HISTORY">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6228" labelText="Age at first mammogram"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6328" labelText="Date of recent mammogram"/>
                </td>
            </tr>
        </table>
    </section>
    <section headerLabel="6. Family history">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6285" labelText="Breast cancer" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6238" labelText="Ovarian Cancer" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6240" labelText="Colon cancer" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6244" labelText="Prostate cancer" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6246" labelText="Other cancer" style="checkbox"/>
                </td>
            </tr>
        </table>
    </section>
    <!--||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||-->

    <section headerLabel="7. Past medical history">
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6243" labelText="Allergies" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6248" labelText="Anxiety/depression" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6251" labelText="Bleeding/clotting disorder" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6256" labelText="Heart burn/acid reflux" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6254" labelText="Osteoporosis" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6252" labelText="Sleeping disorder" style="checkbox"/>
                </td>
            </tr>
            <tr>
                <td>
                    <obs conceptId="6253" labelText="Thyroid disorder" style="checkbox"/>
                </td>
            </tr>
             <tr>
                <td>
                     <obs conceptId="6336" labelText="Have you ever been diagnosed with cancer (excluding breast cancer)?"/>
                </td>
             </tr>
        </table>
    </section>
    <section headerLabel="8. LIFE STYLE">
        <table class="baseline-aligned">
            <tr>
                    <td>a.Have you ever been exposed to industrial chemicals or radiation?</td>
                    <td>
                        <obs conceptId="6332" style="yes_no"/>
                    </td>
                </tr>
            <tr>
                <td>b.Do you smoke?</td>
                <td>
                    <obs conceptId="6333" style="yes_no"/>
                </td>
            </tr>
            <tr>
                <td>c.Do you have a personal history of recreational drug use?</td>
                <td>
                    <obs conceptId="6334" style="yes_no"/>
                </td>
            </tr>
            <tr>
                <td>d.Do you have a personal history of alcoholism?</td>
                <td>
                    <obs conceptId="6335" style="yes_no"/>
                </td>
            </tr>
           </table>
    </section>
    <!--||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||-->
    <section>
        <table class="baseline-aligned">
            <tr>
                <td>
                    <obs conceptId="6153" id="patientstage" labelText="Breast cancer stages" required="true"/>
                </td>
                <td>
                    <div style="display:none; float: right;" id="stageDiv"><a onclick="showStageInfo()">
                        <img src="https://iu.box.com/shared/static/g96bet64oxomphgt8tykox8ebyhf8mjo.png"/></a></div>
                </td>
            </tr>
        </table>
    </section>

    <div id="dialog" style="display: none; width: 500px;" title="Patient Brochure">
        <p id="stageDialog" class="printable"></p>
        <button type="button" onclick="window.print()">Print</button>
    </div>
    <submit/>
</htmlform>
