newsletter-help
===============

created my first newsletter using generic responsive code,
seems to work ok, but the main paragraphs that span left to right, take up 100% width when you shrink the screen..

could you guys help check to see if this code is good to send for responsive email..

it's my first time coding a newsletter, any help would be appreciated!

   <html xmlns="http://www.w3.org/1999/xhtml">
    <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>Schulte Research Report</title>
    <style type="text/css">
    @media screen and (max-width: 600px) {
    /**** Hide content/sections in mobile ****/
    *[class="No_mobile"] {
        display: none !important;
    }
    /**** Wrap/Re-size any fixed dimension table to any desired width ****/        
    table[class="Fluid_wrapper"] {
        width: 100% !important;
        height: auto;
    }
    /**** Re-size any Image to any desired width ****/        
    img[class="Re-size_image_to_320"] {
        width: 100% !important;
        height: auto;
    }
    /**** Split cells and stack them ****/            
    td[class="Split_cells"] {
        width: 87% !important;
        height: auto;
        float: left;
        padding: 7% 6.5% 0px 6.5%;
    }
    /**** Enhance heading text in mobile ****/            
    td[class="Heading"] {
        border-bottom: 1px solid #888888;
        padding: 10px 0 10px 0;
        height: auto;
    }
    /**** Enhance paragraph text in mobile ****/            
    td[class="Paragraph"] {
        border-bottom: 1px solid #888888;
        padding: 10px 20px 10px 20px;
        height: auto;
        width: 90% !important;
        margin-left: 20px;
    }
    /**** Enhance links such that it becomes a finger tapable button ****/        
    a[class="Mobile_cta"] {
        width: auto;
        height: auto;
        border: 1px solid #2893bf;
        padding: 5px 20px;
        border-radius: 8px;
        display: block;
        text-decoration: none !important;
        font-size: 13px !important;
    }
    img[class="Fluid_image"] {
        width: 70% !important;
        height: auto;
    }
    
    </style>
    </head>
     
    <body yahoo style="margin: 0; padding: 0; background: #eaeaea">
    <!-- 100% wrapper table -->
    <table width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#fff">
      <tr>
        <td align="left" valign="top"><!-- 600px fixed center aligned wrapper table -->
     
          <table width="600" border="0" cellspacing="0" cellpadding="0" align="center" class="Fluid_wrapper">
            <tr>
              <td align="left" valign="top" bgcolor="#636468"><!-- Header section -->
     
                <table width="100%" border="0" cellspacing="0" cellpadding="0">
                  <tr>
                    <td height="33" align="left" bgcolor="#d4d4d4" style="font-family: Tahoma, Geneva, sans-serif;text-transform: uppercase;color: #989e9e;font-size: 10px;padding-left: 5px;">Schulte Research Report</td>
    </tr>
    </table>
     
                <!-- Header section --></td>
            </tr>
            <tr>
              <td style="padding: 25px 0 5px 0;" align="center" valign="middle" bgcolor="#FFFFFF"><!-- Re-sizeable Banner Image section --> 
                <img class="Fluid_image" src="http://www.antonpelayo.com/shulte/images/logo.png" alt="Shulte Research Logo" border="0" style="display:block;" /> 
                <!-- Re-sizeable Banner Image section --></td>
            </tr>
            <tr>
              <td align="left" valign="top" bgcolor="#FFFFFF"><!-- Content section -->
     
                <table width="100%" border="0" cellspacing="0" cellpadding="0">
                  <tr>
                    <td align="left" valign="top" height="20" class="No_mobile"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="20" alt="" style="display:block;" /></td>
                  </tr>
                  <tr>
                    <td align="left" valign="top"><table width="100%" border="0" cellspacing="0" cellpadding="0">
                        <tr>
    
                  
                  <!-- Main -->
                  
                  <td align="left" valign="top" class="Split_cells"><table width="98%"  border="0" cellspacing="0" cellpadding="0">
                              <tr>
                                <td class="Heading" style="font-family: Arial, Helvetica, sans-serif; font-size: 20px; color: #353e44; text-decoration: none; line-height: 24px;" align="center" valign="middle" bgcolor="#d4d4d4" height="192">
                                <h1 style="font-family: Tahoma, Geneva, sans-serif;font-size: 24px;font-weight: bold;text-transform: uppercase;color: #434344;line-height: 24px;">SCHULTE RESEARCH REPORT: EDITION 63</h1>
                                
                                <h2 class="h2style" style="font-family:Arial, Gadget, sans-serif; font-size: 16px;font-weight: bold;color: #a1a1a1;line-height: 19px; padding: 0 5px 0 5px;">China Credit Check: All Signals Indicate A Benign Scenario</h2>
        
        <p class="p-title" style="font-family: Arial, Helvetica, sans-serif;font-size: 14px;line-height: 14px;font-weight: normal;font-variant: normal;text-transform: none;color: #a1a1a1;">Tuesday October 28, 2014</p>
        
        </td>
        </tr>
        
        <tr>
        <td align="left" valign="top" height="14"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
         </tr>
                              <tr>
                               <!-- Bullet -->
                               <td align="left" valign="top" style="font-family: MS Serif,New York, serif;font-size: 18px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: 10px;">&bull; Interbank rates are near old lows. The CNY wants to appreciate. Signs of distress are absent.</td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" height="14"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" style="font-family: MS Serif,New York, serif;font-size: 18px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: 10px;">&bull; Net foreign assets are at new highs. Inflation is subdued. Real Rates are very high and have room to fall.</td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" height="14"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
                              </tr>
                              <tr>
                               <td align="left" valign="top" style="font-family: MS Serif,New York, serif;font-size: 18px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: 10px;">&bull; We conducted a credit test on the bonds for China and only about 5% are at risk. Oil, technology and conglomerates are in good shape.</td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" height="14"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
                              </tr>
    
                              <tr>
                                <td align="left" valign="top" style="font-family: Arial, Helvetica, sans-serif; font-size: 12px; color: #353e44; text-decoration: none; line-height: 16px;">&nbsp;</td>
                              </tr>
                          </table></td>
                          <td align="left" valign="top" width="10" class="No_mobile"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="10" height="1" alt="" style="display:block;" /></td>
                          <td align="left" valign="top" width="158" class="Split_cells"><table width="100%" border="0" cellspacing="0" cellpadding="0" class="Border_top">
                              <tr>
                                <td align="left" valign="top" class="Fluid_image"  bgcolor="#D4D4D4" style="font-family: Arial, Helvetica, sans-serif;font-size: 15px;font-weight: bold;font-variant: normal;text-transform: uppercase;color: #FFF;text-decoration: none;text-align: center;padding-top: 5px;padding-right: 5px;padding-bottom: 5px;padding-left: 5px;display:block;">
    
    <img src="http://www.antonpelayo.com/shulte/images/paul.png" height="162" alt="Paul Shulte" /></td>
                              </tr>
     <tr>
                                <td align="center" valign="middle" height="20" bgcolor="#434344" style="font-family: Arial, Helvetica, sans-serif; font-size: 12px; color: #353e44; text-decoration: none; line-height: 16px;"><a href="http://www.antonpelayo.com/shulte/watchvideo.mp4" target="_blank" class="video" style="font-family: Arial, Helvetica, sans-serif;font-size: 15px;font-weight: bold;font-variant: normal;text-transform: uppercase;color: #FFF;text-decoration: none;text-align: center;padding-top: 5px;padding-right: 5px;padding-bottom: 5px;padding-left: 5px;">Watch the video</a></td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" height="14"><img src="images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" style="font-family: Arial, Helvetica, sans-serif; font-size: 12px; color: #353e44; text-decoration: none; line-height: 16px;"><h3 style="font-family: &quot;MS Serif&quot;, &quot;New York&quot;, serif;font-size: 16px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 16px;margin-top: 0px;margin-bottom: -5px;">Contact us</h3>
         
          <p class="contact" style="font-size: 11px;line-height: 13px;font-weight: normal;font-variant: normal;text-transform: none;color: #202020;font-family: Tahoma, Geneva, sans-serif;">Paul Schulte<br />
            Founder and Editor<br />
            +852 9705 0777<br />
            paul@schulte-research.com<br />
      <br />
            Gavin Liu<br />
            +852 2534 7419<br />
            gavin@schulte-research.com<br />
      <br />
            Christian Ng<br />
            +852 2534 7417<br />
        christian@schulte-research.com</p></td>
                              </tr>
                              <tr>
                                <td align="left" valign="top" height="14"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="14" alt="" style="display:block;" /></td>
                              </tr>
    
                            </table></td>
    
                        </tr>
                      </table></td>
                  </tr>
                  <tr>
                    <td align="left" valign="top" height="20"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="1" height="20" alt="" style="display:block;" /></td>
                  </tr>
                </table>
     
                <!-- Content section --></td>
            </tr>
            <tr>
              <td align="center" valign="top" >
              
               <table width="100%" border="0" cellspacing="0" cellpadding="0">
                  <tr class="Paragraph">
                    <td height="33"  style="margin-top: 0px;font-size: 16px;line-height: normal;font-weight: normal;color: #202020;border-top-width: 1px;border-bottom-width: 0px;border-top-style: solid;border-bottom-style: solid;border-top-color: #202020;border-right-color: #202020;border-bottom-color: #202020;border-left-color: #202020;padding-top: 30px;padding-bottom: 45px;">
                    
                        <h3 style="font-family: MS Serif, New York, serif; font-size: 20px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: -10px;">Where’s the impending crisis that all the bears are talking about?</h3>
        <p>Xi Jinping’s administration is administering a major cleanout and reforms are now embedded. None of the telltale signs of crisis are present. The government is deliberately orchestrating a squeeze in property to cause prices to move sideways. They offered liquidity to the market and have full control of liquidity given very high surpluses.</p>
        
    </td>
    </tr>
    
                  <tr>
                    <td height="33"  style="margin-top: 0px;font-size: 16px;line-height: normal;font-weight: normal;color: #202020;border-top-width: 1px;border-bottom-width: 0px;border-top-style: solid;border-bottom-style: solid;border-top-color: #202020;border-right-color: #202020;border-bottom-color: #202020;border-left-color: #202020;padding-top: 30px;padding-bottom: 45px;">
                    
                        <h3 style="font-family: MS Serif, New York, serif; font-size: 20px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: -10px;">We conducted a credit check of the bonds valued at $400 bn using the Altman Z score.</h3>
        <p>This z score is excellent at picking up problems. These bonds are almost all trading at or around 100 with yields at about 5%. Today, we look at the healthiest. This group is comprised oil, and technology. 85% is oil. Shenhua and Sinochem offer safety and value. CNOOC is very safe but yields 3.5% averagely.</p>
        
    </td>
    </tr>
    
    <tr>
              <td style="border-top-width: 1px;border-bottom-width: 0px;border-top-style: solid;border-bottom-style: solid;border-top-color: #202020;border-right-color: #202020;border-bottom-color: #202020;border-left-color: #202020;padding: 25px 0 45px 0;" align="center" valign="middle" bgcolor="#FFFFFF" ><!-- Re-sizeable Banner Image section --> 
                <img class="Fluid_image" src="http://www.antonpelayo.com/shulte/images/chart.jpg" alt="Chart of the week" border="0" style="display:block;" /> 
                <!-- Re-sizeable Banner Image section --></td>
            </tr>
            
                  <tr>
                    <td height="33"  style="margin-top: 0px;font-size: 16px;line-height: normal;font-weight: normal;color: #202020;border-top-width: 1px;border-bottom-width: 0px;border-top-style: solid;border-bottom-style: solid;border-top-color: #202020;border-right-color: #202020;border-bottom-color: #202020;border-left-color: #202020;padding-top: 30px;padding-bottom: 45px;">
                    
                        <h3 style="font-family: MS Serif, New York, serif; font-size: 20px;font-weight: bolder;font-variant: normal;text-transform: uppercase;color: #538dd5;text-decoration: none;line-height: 20px;margin-top: 20px;margin-bottom: -10px;">Those with average credit scores (denoting safety but possible problems) include COLI (5%) and Shaanxi Coal (5.5%). </h3>
        <p>In the next few days we will look at those which failed the test. These are utilities and rail (and Country Garden).  These need balance sheet restructuring which is bad for equity holders.</p>
        
    </td>
    </tr>
    </table>
              
              <!-- Footer section -->
     
                <table width="100%" border="0" cellspacing="0" cellpadding="0" bgcolor="#d4d4d4">
                  <tr>
                    <td align="left" valign="top"><table width="100%" border="0" cellspacing="0" cellpadding="0">
                        <tr>
                          <td align="left" valign="top" width="21"><img src="images/spacer.gif" width="21" height="1" alt="" style="display:block;" /></td>
                          <td align="left" valign="middle" bgcolor="#d4d4d4" class="Heading" height="100px" style="font-family: Arial, Helvetica, sans-serif;font-size: 10px;font-weight: normal;color: #1f1f1f;line-height: normal;letter-spacing: normal;text-align: center;">You are receiving this email as a client and friend of Schulte Research. This report is exclusively for our clients. Please help us protect the exclusivity of this service by not forwarding it to others. For independent research to survive, the integrity of our products and services has to be maintained. All products and/or correspondence should only be received by paying clients of Schulte Research. If you have received this report in error, please delete it or contact us about how to become a client.</td>
                          <td align="left" valign="top" width="21"><img src="http://www.antonpelayo.com/shulte/images/spacer.gif" width="21" height="1" alt="" style="display:block;" /></td>
                        </tr>
                      </table></td>
                  </tr>
    
                </table>
     
                <!-- Footer section --></td>
            </tr>
          </table>
     
          <!-- 600px fixed center aligned wrapper table --></td>
      </tr>
    </table>
    <!-- 100% wrapper table -->
    </body>
    </html>
