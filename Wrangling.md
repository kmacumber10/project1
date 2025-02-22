<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20243.24.1211.0901                               -->
<workbook original-version='18.1' source-build='2024.3.2 (20243.24.1211.0901)' source-platform='mac' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <AnimationOnByDefault />
    <IntuitiveSorting />
    <IntuitiveSorting_SP2 />
    <MarkAnimation />
    <ObjectModelEncapsulateLegacy />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
    <SheetIdentifierTracking />
    <WindowsPersistSimpleIdentifiers />
  </document-format-change-manifest>
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <datasources>
    <datasource caption='L.A.csv (Multiple Connections)' inline='true' name='federated.014yrua12d58ti17ud8qi1s9fkgl' version='18.1'>
      <connection class='federated'>
        <named-connections>
          <named-connection caption='L.A' name='textscan.1hzm83v0hh3qx81e9epif1p6bs7f'>
            <connection class='textscan' directory='/Users/keeganmacumber/Downloads' filename='L.A.csv' password='' server='' />
          </named-connection>
          <named-connection caption='MTL' name='textscan.0941o281h8woyl19qm5gh18au2o9'>
            <connection class='textscan' directory='/Users/keeganmacumber/Downloads' filename='MTL.csv' password='' server='' />
          </named-connection>
          <named-connection caption='TOR' name='textscan.06o0rr612lui8a15l9st313nz054'>
            <connection class='textscan' directory='/Users/keeganmacumber/Downloads' filename='TOR.csv' password='' server='' />
          </named-connection>
          <named-connection caption='S.J' name='textscan.1shacmw07tn87g19otj2j1skyie0'>
            <connection class='textscan' directory='/Users/keeganmacumber/Downloads' filename='S.J.csv' password='' server='' />
          </named-connection>
        </named-connections>
        <relation connection='textscan.1hzm83v0hh3qx81e9epif1p6bs7f' name='L.A.csv' table='[L.A#csv]' type='table'>
          <columns character-set='UTF-8' header='yes' locale='en_CA' separator=','>
            <column datatype='string' name='team' ordinal='0' />
            <column datatype='integer' name='season' ordinal='1' />
            <column datatype='string' name='name' ordinal='2' />
            <column datatype='integer' name='gameId' ordinal='3' />
            <column datatype='string' name='playerTeam' ordinal='4' />
            <column datatype='string' name='opposingTeam' ordinal='5' />
            <column datatype='string' name='home_or_away' ordinal='6' />
            <column datatype='date' name='gameDate' ordinal='7' />
            <column datatype='string' name='position' ordinal='8' />
            <column datatype='string' name='situation' ordinal='9' />
            <column datatype='real' name='xGoalsPercentage' ordinal='10' />
            <column datatype='real' name='corsiPercentage' ordinal='11' />
            <column datatype='real' name='fenwickPercentage' ordinal='12' />
            <column datatype='real' name='iceTime' ordinal='13' />
            <column datatype='real' name='xOnGoalFor' ordinal='14' />
            <column datatype='real' name='xGoalsFor' ordinal='15' />
            <column datatype='real' name='xReboundsFor' ordinal='16' />
            <column datatype='real' name='xFreezeFor' ordinal='17' />
            <column datatype='real' name='xPlayStoppedFor' ordinal='18' />
            <column datatype='real' name='xPlayContinuedInZoneFor' ordinal='19' />
            <column datatype='real' name='xPlayContinuedOutsideZoneFor' ordinal='20' />
            <column datatype='real' name='flurryAdjustedxGoalsFor' ordinal='21' />
            <column datatype='real' name='scoreVenueAdjustedxGoalsFor' ordinal='22' />
            <column datatype='real' name='flurryScoreVenueAdjustedxGoalsFor' ordinal='23' />
            <column datatype='real' name='shotsOnGoalFor' ordinal='24' />
            <column datatype='real' name='missedShotsFor' ordinal='25' />
            <column datatype='real' name='blockedShotAttemptsFor' ordinal='26' />
            <column datatype='real' name='shotAttemptsFor' ordinal='27' />
            <column datatype='real' name='goalsFor' ordinal='28' />
            <column datatype='real' name='reboundsFor' ordinal='29' />
            <column datatype='real' name='reboundGoalsFor' ordinal='30' />
            <column datatype='real' name='freezeFor' ordinal='31' />
            <column datatype='real' name='playStoppedFor' ordinal='32' />
            <column datatype='real' name='playContinuedInZoneFor' ordinal='33' />
            <column datatype='real' name='playContinuedOutsideZoneFor' ordinal='34' />
            <column datatype='real' name='savedShotsOnGoalFor' ordinal='35' />
            <column datatype='real' name='savedUnblockedShotAttemptsFor' ordinal='36' />
            <column datatype='real' name='penaltiesFor' ordinal='37' />
            <column datatype='real' name='penalityMinutesFor' ordinal='38' />
            <column datatype='real' name='faceOffsWonFor' ordinal='39' />
            <column datatype='real' name='hitsFor' ordinal='40' />
            <column datatype='real' name='takeawaysFor' ordinal='41' />
            <column datatype='real' name='giveawaysFor' ordinal='42' />
            <column datatype='real' name='lowDangerShotsFor' ordinal='43' />
            <column datatype='real' name='mediumDangerShotsFor' ordinal='44' />
            <column datatype='real' name='highDangerShotsFor' ordinal='45' />
            <column datatype='real' name='lowDangerxGoalsFor' ordinal='46' />
            <column datatype='real' name='mediumDangerxGoalsFor' ordinal='47' />
            <column datatype='real' name='highDangerxGoalsFor' ordinal='48' />
            <column datatype='real' name='lowDangerGoalsFor' ordinal='49' />
            <column datatype='real' name='mediumDangerGoalsFor' ordinal='50' />
            <column datatype='real' name='highDangerGoalsFor' ordinal='51' />
            <column datatype='real' name='scoreAdjustedShotsAttemptsFor' ordinal='52' />
            <column datatype='real' name='unblockedShotAttemptsFor' ordinal='53' />
            <column datatype='real' name='scoreAdjustedUnblockedShotAttemptsFor' ordinal='54' />
            <column datatype='real' name='dZoneGiveawaysFor' ordinal='55' />
            <column datatype='real' name='xGoalsFromxReboundsOfShotsFor' ordinal='56' />
            <column datatype='real' name='xGoalsFromActualReboundsOfShotsFor' ordinal='57' />
            <column datatype='real' name='reboundxGoalsFor' ordinal='58' />
            <column datatype='real' name='totalShotCreditFor' ordinal='59' />
            <column datatype='real' name='scoreAdjustedTotalShotCreditFor' ordinal='60' />
            <column datatype='real' name='scoreFlurryAdjustedTotalShotCreditFor' ordinal='61' />
            <column datatype='real' name='xOnGoalAgainst' ordinal='62' />
            <column datatype='real' name='xGoalsAgainst' ordinal='63' />
            <column datatype='real' name='xReboundsAgainst' ordinal='64' />
            <column datatype='real' name='xFreezeAgainst' ordinal='65' />
            <column datatype='real' name='xPlayStoppedAgainst' ordinal='66' />
            <column datatype='real' name='xPlayContinuedInZoneAgainst' ordinal='67' />
            <column datatype='real' name='xPlayContinuedOutsideZoneAgainst' ordinal='68' />
            <column datatype='real' name='flurryAdjustedxGoalsAgainst' ordinal='69' />
            <column datatype='real' name='scoreVenueAdjustedxGoalsAgainst' ordinal='70' />
            <column datatype='real' name='flurryScoreVenueAdjustedxGoalsAgainst' ordinal='71' />
            <column datatype='real' name='shotsOnGoalAgainst' ordinal='72' />
            <column datatype='real' name='missedShotsAgainst' ordinal='73' />
            <column datatype='real' name='blockedShotAttemptsAgainst' ordinal='74' />
            <column datatype='real' name='shotAttemptsAgainst' ordinal='75' />
            <column datatype='real' name='goalsAgainst' ordinal='76' />
            <column datatype='real' name='reboundsAgainst' ordinal='77' />
            <column datatype='real' name='reboundGoalsAgainst' ordinal='78' />
            <column datatype='real' name='freezeAgainst' ordinal='79' />
            <column datatype='real' name='playStoppedAgainst' ordinal='80' />
            <column datatype='real' name='playContinuedInZoneAgainst' ordinal='81' />
            <column datatype='real' name='playContinuedOutsideZoneAgainst' ordinal='82' />
            <column datatype='real' name='savedShotsOnGoalAgainst' ordinal='83' />
            <column datatype='real' name='savedUnblockedShotAttemptsAgainst' ordinal='84' />
            <column datatype='real' name='penaltiesAgainst' ordinal='85' />
            <column datatype='real' name='penalityMinutesAgainst' ordinal='86' />
            <column datatype='real' name='faceOffsWonAgainst' ordinal='87' />
            <column datatype='real' name='hitsAgainst' ordinal='88' />
            <column datatype='real' name='takeawaysAgainst' ordinal='89' />
            <column datatype='real' name='giveawaysAgainst' ordinal='90' />
            <column datatype='real' name='lowDangerShotsAgainst' ordinal='91' />
            <column datatype='real' name='mediumDangerShotsAgainst' ordinal='92' />
            <column datatype='real' name='highDangerShotsAgainst' ordinal='93' />
            <column datatype='real' name='lowDangerxGoalsAgainst' ordinal='94' />
            <column datatype='real' name='mediumDangerxGoalsAgainst' ordinal='95' />
            <column datatype='real' name='highDangerxGoalsAgainst' ordinal='96' />
            <column datatype='real' name='lowDangerGoalsAgainst' ordinal='97' />
            <column datatype='real' name='mediumDangerGoalsAgainst' ordinal='98' />
            <column datatype='real' name='highDangerGoalsAgainst' ordinal='99' />
            <column datatype='real' name='scoreAdjustedShotsAttemptsAgainst' ordinal='100' />
            <column datatype='real' name='unblockedShotAttemptsAgainst' ordinal='101' />
            <column datatype='real' name='scoreAdjustedUnblockedShotAttemptsAgainst' ordinal='102' />
            <column datatype='real' name='dZoneGiveawaysAgainst' ordinal='103' />
            <column datatype='real' name='xGoalsFromxReboundsOfShotsAgainst' ordinal='104' />
            <column datatype='real' name='xGoalsFromActualReboundsOfShotsAgainst' ordinal='105' />
            <column datatype='real' name='reboundxGoalsAgainst' ordinal='106' />
            <column datatype='real' name='totalShotCreditAgainst' ordinal='107' />
            <column datatype='real' name='scoreAdjustedTotalShotCreditAgainst' ordinal='108' />
            <column datatype='real' name='scoreFlurryAdjustedTotalShotCreditAgainst' ordinal='109' />
          </columns>
        </relation>
        <metadata-records>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='string' name='character-set'>&quot;UTF-8&quot;</attribute>
              <attribute datatype='string' name='collation'>&quot;en_GB&quot;</attribute>
              <attribute datatype='string' name='field-delimiter'>&quot;,&quot;</attribute>
              <attribute datatype='string' name='header-row'>&quot;true&quot;</attribute>
              <attribute datatype='string' name='locale'>&quot;en_CA&quot;</attribute>
              <attribute datatype='string' name='single-char'>&quot;&quot;</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>team</remote-name>
            <remote-type>129</remote-type>
            <local-name>[team]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>team</remote-alias>
            <ordinal>0</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>season</remote-name>
            <remote-type>20</remote-type>
            <local-name>[season]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>season</remote-alias>
            <ordinal>1</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[name]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>name</remote-alias>
            <ordinal>2</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>gameId</remote-name>
            <remote-type>20</remote-type>
            <local-name>[gameId]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>gameId</remote-alias>
            <ordinal>3</ordinal>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playerTeam</remote-name>
            <remote-type>129</remote-type>
            <local-name>[playerTeam]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playerTeam</remote-alias>
            <ordinal>4</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>opposingTeam</remote-name>
            <remote-type>129</remote-type>
            <local-name>[opposingTeam]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>opposingTeam</remote-alias>
            <ordinal>5</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>home_or_away</remote-name>
            <remote-type>129</remote-type>
            <local-name>[home_or_away]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>home_or_away</remote-alias>
            <ordinal>6</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>gameDate</remote-name>
            <remote-type>133</remote-type>
            <local-name>[gameDate]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>gameDate</remote-alias>
            <ordinal>7</ordinal>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>position</remote-name>
            <remote-type>129</remote-type>
            <local-name>[position]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>position</remote-alias>
            <ordinal>8</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>situation</remote-name>
            <remote-type>129</remote-type>
            <local-name>[situation]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>situation</remote-alias>
            <ordinal>9</ordinal>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <scale>1</scale>
            <width>1073741823</width>
            <contains-null>true</contains-null>
            <collation flag='0' name='LEN_RGB' />
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsPercentage</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsPercentage]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsPercentage</remote-alias>
            <ordinal>10</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>corsiPercentage</remote-name>
            <remote-type>5</remote-type>
            <local-name>[corsiPercentage]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>corsiPercentage</remote-alias>
            <ordinal>11</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>fenwickPercentage</remote-name>
            <remote-type>5</remote-type>
            <local-name>[fenwickPercentage]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>fenwickPercentage</remote-alias>
            <ordinal>12</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>iceTime</remote-name>
            <remote-type>5</remote-type>
            <local-name>[iceTime]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>iceTime</remote-alias>
            <ordinal>13</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xOnGoalFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xOnGoalFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xOnGoalFor</remote-alias>
            <ordinal>14</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsFor</remote-alias>
            <ordinal>15</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xReboundsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xReboundsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xReboundsFor</remote-alias>
            <ordinal>16</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xFreezeFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xFreezeFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xFreezeFor</remote-alias>
            <ordinal>17</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayStoppedFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayStoppedFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayStoppedFor</remote-alias>
            <ordinal>18</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayContinuedInZoneFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayContinuedInZoneFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayContinuedInZoneFor</remote-alias>
            <ordinal>19</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayContinuedOutsideZoneFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayContinuedOutsideZoneFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayContinuedOutsideZoneFor</remote-alias>
            <ordinal>20</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>flurryAdjustedxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[flurryAdjustedxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>flurryAdjustedxGoalsFor</remote-alias>
            <ordinal>21</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreVenueAdjustedxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreVenueAdjustedxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreVenueAdjustedxGoalsFor</remote-alias>
            <ordinal>22</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>flurryScoreVenueAdjustedxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[flurryScoreVenueAdjustedxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>flurryScoreVenueAdjustedxGoalsFor</remote-alias>
            <ordinal>23</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shotsOnGoalFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[shotsOnGoalFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>shotsOnGoalFor</remote-alias>
            <ordinal>24</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>missedShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[missedShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>missedShotsFor</remote-alias>
            <ordinal>25</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>blockedShotAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[blockedShotAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>blockedShotAttemptsFor</remote-alias>
            <ordinal>26</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shotAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[shotAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>shotAttemptsFor</remote-alias>
            <ordinal>27</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>goalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[goalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>goalsFor</remote-alias>
            <ordinal>28</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundsFor</remote-alias>
            <ordinal>29</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundGoalsFor</remote-alias>
            <ordinal>30</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>freezeFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[freezeFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>freezeFor</remote-alias>
            <ordinal>31</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playStoppedFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playStoppedFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playStoppedFor</remote-alias>
            <ordinal>32</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playContinuedInZoneFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playContinuedInZoneFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playContinuedInZoneFor</remote-alias>
            <ordinal>33</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playContinuedOutsideZoneFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playContinuedOutsideZoneFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playContinuedOutsideZoneFor</remote-alias>
            <ordinal>34</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>savedShotsOnGoalFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[savedShotsOnGoalFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>savedShotsOnGoalFor</remote-alias>
            <ordinal>35</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>savedUnblockedShotAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[savedUnblockedShotAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>savedUnblockedShotAttemptsFor</remote-alias>
            <ordinal>36</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>penaltiesFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[penaltiesFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>penaltiesFor</remote-alias>
            <ordinal>37</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>penalityMinutesFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[penalityMinutesFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>penalityMinutesFor</remote-alias>
            <ordinal>38</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>faceOffsWonFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[faceOffsWonFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>faceOffsWonFor</remote-alias>
            <ordinal>39</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>hitsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[hitsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>hitsFor</remote-alias>
            <ordinal>40</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>takeawaysFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[takeawaysFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>takeawaysFor</remote-alias>
            <ordinal>41</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>giveawaysFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[giveawaysFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>giveawaysFor</remote-alias>
            <ordinal>42</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerShotsFor</remote-alias>
            <ordinal>43</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerShotsFor</remote-alias>
            <ordinal>44</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerShotsFor</remote-alias>
            <ordinal>45</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerxGoalsFor</remote-alias>
            <ordinal>46</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerxGoalsFor</remote-alias>
            <ordinal>47</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerxGoalsFor</remote-alias>
            <ordinal>48</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerGoalsFor</remote-alias>
            <ordinal>49</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerGoalsFor</remote-alias>
            <ordinal>50</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerGoalsFor</remote-alias>
            <ordinal>51</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedShotsAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedShotsAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedShotsAttemptsFor</remote-alias>
            <ordinal>52</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>unblockedShotAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[unblockedShotAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>unblockedShotAttemptsFor</remote-alias>
            <ordinal>53</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedUnblockedShotAttemptsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedUnblockedShotAttemptsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedUnblockedShotAttemptsFor</remote-alias>
            <ordinal>54</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>dZoneGiveawaysFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[dZoneGiveawaysFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>dZoneGiveawaysFor</remote-alias>
            <ordinal>55</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsFromxReboundsOfShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsFromxReboundsOfShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsFromxReboundsOfShotsFor</remote-alias>
            <ordinal>56</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsFromActualReboundsOfShotsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsFromActualReboundsOfShotsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsFromActualReboundsOfShotsFor</remote-alias>
            <ordinal>57</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundxGoalsFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundxGoalsFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundxGoalsFor</remote-alias>
            <ordinal>58</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>totalShotCreditFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[totalShotCreditFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>totalShotCreditFor</remote-alias>
            <ordinal>59</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedTotalShotCreditFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedTotalShotCreditFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedTotalShotCreditFor</remote-alias>
            <ordinal>60</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreFlurryAdjustedTotalShotCreditFor</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreFlurryAdjustedTotalShotCreditFor]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreFlurryAdjustedTotalShotCreditFor</remote-alias>
            <ordinal>61</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xOnGoalAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xOnGoalAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xOnGoalAgainst</remote-alias>
            <ordinal>62</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsAgainst</remote-alias>
            <ordinal>63</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xReboundsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xReboundsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xReboundsAgainst</remote-alias>
            <ordinal>64</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xFreezeAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xFreezeAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xFreezeAgainst</remote-alias>
            <ordinal>65</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayStoppedAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayStoppedAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayStoppedAgainst</remote-alias>
            <ordinal>66</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayContinuedInZoneAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayContinuedInZoneAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayContinuedInZoneAgainst</remote-alias>
            <ordinal>67</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xPlayContinuedOutsideZoneAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xPlayContinuedOutsideZoneAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xPlayContinuedOutsideZoneAgainst</remote-alias>
            <ordinal>68</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>flurryAdjustedxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[flurryAdjustedxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>flurryAdjustedxGoalsAgainst</remote-alias>
            <ordinal>69</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreVenueAdjustedxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreVenueAdjustedxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreVenueAdjustedxGoalsAgainst</remote-alias>
            <ordinal>70</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>flurryScoreVenueAdjustedxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[flurryScoreVenueAdjustedxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>flurryScoreVenueAdjustedxGoalsAgainst</remote-alias>
            <ordinal>71</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shotsOnGoalAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[shotsOnGoalAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>shotsOnGoalAgainst</remote-alias>
            <ordinal>72</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>missedShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[missedShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>missedShotsAgainst</remote-alias>
            <ordinal>73</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>blockedShotAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[blockedShotAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>blockedShotAttemptsAgainst</remote-alias>
            <ordinal>74</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>shotAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[shotAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>shotAttemptsAgainst</remote-alias>
            <ordinal>75</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>goalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[goalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>goalsAgainst</remote-alias>
            <ordinal>76</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundsAgainst</remote-alias>
            <ordinal>77</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundGoalsAgainst</remote-alias>
            <ordinal>78</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>freezeAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[freezeAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>freezeAgainst</remote-alias>
            <ordinal>79</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playStoppedAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playStoppedAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playStoppedAgainst</remote-alias>
            <ordinal>80</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playContinuedInZoneAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playContinuedInZoneAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playContinuedInZoneAgainst</remote-alias>
            <ordinal>81</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>playContinuedOutsideZoneAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[playContinuedOutsideZoneAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>playContinuedOutsideZoneAgainst</remote-alias>
            <ordinal>82</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>savedShotsOnGoalAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[savedShotsOnGoalAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>savedShotsOnGoalAgainst</remote-alias>
            <ordinal>83</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>savedUnblockedShotAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[savedUnblockedShotAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>savedUnblockedShotAttemptsAgainst</remote-alias>
            <ordinal>84</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>penaltiesAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[penaltiesAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>penaltiesAgainst</remote-alias>
            <ordinal>85</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>penalityMinutesAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[penalityMinutesAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>penalityMinutesAgainst</remote-alias>
            <ordinal>86</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>faceOffsWonAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[faceOffsWonAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>faceOffsWonAgainst</remote-alias>
            <ordinal>87</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>hitsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[hitsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>hitsAgainst</remote-alias>
            <ordinal>88</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>takeawaysAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[takeawaysAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>takeawaysAgainst</remote-alias>
            <ordinal>89</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>giveawaysAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[giveawaysAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>giveawaysAgainst</remote-alias>
            <ordinal>90</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerShotsAgainst</remote-alias>
            <ordinal>91</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerShotsAgainst</remote-alias>
            <ordinal>92</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerShotsAgainst</remote-alias>
            <ordinal>93</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerxGoalsAgainst</remote-alias>
            <ordinal>94</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerxGoalsAgainst</remote-alias>
            <ordinal>95</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerxGoalsAgainst</remote-alias>
            <ordinal>96</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>lowDangerGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[lowDangerGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>lowDangerGoalsAgainst</remote-alias>
            <ordinal>97</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>mediumDangerGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[mediumDangerGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>mediumDangerGoalsAgainst</remote-alias>
            <ordinal>98</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>highDangerGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[highDangerGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>highDangerGoalsAgainst</remote-alias>
            <ordinal>99</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedShotsAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedShotsAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedShotsAttemptsAgainst</remote-alias>
            <ordinal>100</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>unblockedShotAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[unblockedShotAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>unblockedShotAttemptsAgainst</remote-alias>
            <ordinal>101</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedUnblockedShotAttemptsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedUnblockedShotAttemptsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedUnblockedShotAttemptsAgainst</remote-alias>
            <ordinal>102</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>dZoneGiveawaysAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[dZoneGiveawaysAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>dZoneGiveawaysAgainst</remote-alias>
            <ordinal>103</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsFromxReboundsOfShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsFromxReboundsOfShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsFromxReboundsOfShotsAgainst</remote-alias>
            <ordinal>104</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>xGoalsFromActualReboundsOfShotsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[xGoalsFromActualReboundsOfShotsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>xGoalsFromActualReboundsOfShotsAgainst</remote-alias>
            <ordinal>105</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>reboundxGoalsAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[reboundxGoalsAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>reboundxGoalsAgainst</remote-alias>
            <ordinal>106</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>totalShotCreditAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[totalShotCreditAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>totalShotCreditAgainst</remote-alias>
            <ordinal>107</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreAdjustedTotalShotCreditAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreAdjustedTotalShotCreditAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreAdjustedTotalShotCreditAgainst</remote-alias>
            <ordinal>108</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>scoreFlurryAdjustedTotalShotCreditAgainst</remote-name>
            <remote-type>5</remote-type>
            <local-name>[scoreFlurryAdjustedTotalShotCreditAgainst]</local-name>
            <parent-name>[L.A.csv]</parent-name>
            <remote-alias>scoreFlurryAdjustedTotalShotCreditAgainst</remote-alias>
            <ordinal>109</ordinal>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <object-id>[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]</object-id>
          </metadata-record>
        </metadata-records>
      </connection>
      <aliases enabled='yes' />
      <column caption='L.A.csv' datatype='table' name='[__tableau_internal_object_id__].[L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F]' role='measure' type='quantitative' />
      <column caption='Blocked Shot Attempts Against' datatype='real' name='[blockedShotAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Blocked Shot Attempts For' datatype='real' name='[blockedShotAttemptsFor]' role='measure' type='quantitative' />
      <column caption='Corsi Percentage' datatype='real' name='[corsiPercentage]' role='measure' type='quantitative' />
      <column caption='D Zone Giveaways Against' datatype='real' name='[dZoneGiveawaysAgainst]' role='measure' type='quantitative' />
      <column caption='D Zone Giveaways For' datatype='real' name='[dZoneGiveawaysFor]' role='measure' type='quantitative' />
      <column caption='Face Offs Won Against' datatype='real' name='[faceOffsWonAgainst]' role='measure' type='quantitative' />
      <column caption='Face Offs Won For' datatype='real' name='[faceOffsWonFor]' role='measure' type='quantitative' />
      <column caption='Fenwick Percentage' datatype='real' name='[fenwickPercentage]' role='measure' type='quantitative' />
      <column caption='Flurry Adjustedx Goals Against' datatype='real' name='[flurryAdjustedxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Flurry Adjustedx Goals For' datatype='real' name='[flurryAdjustedxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Flurry Score Venue Adjustedx Goals Against' datatype='real' name='[flurryScoreVenueAdjustedxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Flurry Score Venue Adjustedx Goals For' datatype='real' name='[flurryScoreVenueAdjustedxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Freeze Against' datatype='real' name='[freezeAgainst]' role='measure' type='quantitative' />
      <column caption='Freeze For' datatype='real' name='[freezeFor]' role='measure' type='quantitative' />
      <column caption='Game Date' datatype='date' name='[gameDate]' role='dimension' type='ordinal' />
      <column caption='Game Id' datatype='integer' name='[gameId]' role='dimension' type='ordinal' />
      <column caption='Giveaways Against' datatype='real' name='[giveawaysAgainst]' role='measure' type='quantitative' />
      <column caption='Giveaways For' datatype='real' name='[giveawaysFor]' role='measure' type='quantitative' />
      <column caption='Goals Against' datatype='real' name='[goalsAgainst]' role='measure' type='quantitative' />
      <column caption='Goals For' datatype='real' name='[goalsFor]' role='measure' type='quantitative' />
      <column caption='High Danger Goals Against' datatype='real' name='[highDangerGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='High Danger Goals For' datatype='real' name='[highDangerGoalsFor]' role='measure' type='quantitative' />
      <column caption='High Danger Shots Against' datatype='real' name='[highDangerShotsAgainst]' role='measure' type='quantitative' />
      <column caption='High Danger Shots For' datatype='real' name='[highDangerShotsFor]' role='measure' type='quantitative' />
      <column caption='High Dangerx Goals Against' datatype='real' name='[highDangerxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='High Dangerx Goals For' datatype='real' name='[highDangerxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Hits Against' datatype='real' name='[hitsAgainst]' role='measure' type='quantitative' />
      <column caption='Hits For' datatype='real' name='[hitsFor]' role='measure' type='quantitative' />
      <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
      <column caption='Ice Time' datatype='real' name='[iceTime]' role='measure' type='quantitative' />
      <column caption='Low Danger Goals Against' datatype='real' name='[lowDangerGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Low Danger Goals For' datatype='real' name='[lowDangerGoalsFor]' role='measure' type='quantitative' />
      <column caption='Low Danger Shots Against' datatype='real' name='[lowDangerShotsAgainst]' role='measure' type='quantitative' />
      <column caption='Low Danger Shots For' datatype='real' name='[lowDangerShotsFor]' role='measure' type='quantitative' />
      <column caption='Low Dangerx Goals Against' datatype='real' name='[lowDangerxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Low Dangerx Goals For' datatype='real' name='[lowDangerxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Medium Danger Goals Against' datatype='real' name='[mediumDangerGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Medium Danger Goals For' datatype='real' name='[mediumDangerGoalsFor]' role='measure' type='quantitative' />
      <column caption='Medium Danger Shots Against' datatype='real' name='[mediumDangerShotsAgainst]' role='measure' type='quantitative' />
      <column caption='Medium Danger Shots For' datatype='real' name='[mediumDangerShotsFor]' role='measure' type='quantitative' />
      <column caption='Medium Dangerx Goals Against' datatype='real' name='[mediumDangerxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Medium Dangerx Goals For' datatype='real' name='[mediumDangerxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Missed Shots Against' datatype='real' name='[missedShotsAgainst]' role='measure' type='quantitative' />
      <column caption='Missed Shots For' datatype='real' name='[missedShotsFor]' role='measure' type='quantitative' />
      <column caption='Name' datatype='string' name='[name]' role='dimension' type='nominal' />
      <column caption='Opposing Team' datatype='string' name='[opposingTeam]' role='dimension' type='nominal' />
      <column caption='Penality Minutes Against' datatype='real' name='[penalityMinutesAgainst]' role='measure' type='quantitative' />
      <column caption='Penality Minutes For' datatype='real' name='[penalityMinutesFor]' role='measure' type='quantitative' />
      <column caption='Penalties Against' datatype='real' name='[penaltiesAgainst]' role='measure' type='quantitative' />
      <column caption='Penalties For' datatype='real' name='[penaltiesFor]' role='measure' type='quantitative' />
      <column caption='Play Continued In Zone Against' datatype='real' name='[playContinuedInZoneAgainst]' role='measure' type='quantitative' />
      <column caption='Play Continued In Zone For' datatype='real' name='[playContinuedInZoneFor]' role='measure' type='quantitative' />
      <column caption='Play Continued Outside Zone Against' datatype='real' name='[playContinuedOutsideZoneAgainst]' role='measure' type='quantitative' />
      <column caption='Play Continued Outside Zone For' datatype='real' name='[playContinuedOutsideZoneFor]' role='measure' type='quantitative' />
      <column caption='Play Stopped Against' datatype='real' name='[playStoppedAgainst]' role='measure' type='quantitative' />
      <column caption='Play Stopped For' datatype='real' name='[playStoppedFor]' role='measure' type='quantitative' />
      <column caption='Player Team' datatype='string' name='[playerTeam]' role='dimension' type='nominal' />
      <column caption='Position' datatype='string' name='[position]' role='dimension' type='nominal' />
      <column caption='Rebound Goals Against' datatype='real' name='[reboundGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Rebound Goals For' datatype='real' name='[reboundGoalsFor]' role='measure' type='quantitative' />
      <column caption='Rebounds Against' datatype='real' name='[reboundsAgainst]' role='measure' type='quantitative' />
      <column caption='Rebounds For' datatype='real' name='[reboundsFor]' role='measure' type='quantitative' />
      <column caption='Reboundx Goals Against' datatype='real' name='[reboundxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Reboundx Goals For' datatype='real' name='[reboundxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Saved Shots On Goal Against' datatype='real' name='[savedShotsOnGoalAgainst]' role='measure' type='quantitative' />
      <column caption='Saved Shots On Goal For' datatype='real' name='[savedShotsOnGoalFor]' role='measure' type='quantitative' />
      <column caption='Saved Unblocked Shot Attempts Against' datatype='real' name='[savedUnblockedShotAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Saved Unblocked Shot Attempts For' datatype='real' name='[savedUnblockedShotAttemptsFor]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Shots Attempts Against' datatype='real' name='[scoreAdjustedShotsAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Shots Attempts For' datatype='real' name='[scoreAdjustedShotsAttemptsFor]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Total Shot Credit Against' datatype='real' name='[scoreAdjustedTotalShotCreditAgainst]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Total Shot Credit For' datatype='real' name='[scoreAdjustedTotalShotCreditFor]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Unblocked Shot Attempts Against' datatype='real' name='[scoreAdjustedUnblockedShotAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Score Adjusted Unblocked Shot Attempts For' datatype='real' name='[scoreAdjustedUnblockedShotAttemptsFor]' role='measure' type='quantitative' />
      <column caption='Score Flurry Adjusted Total Shot Credit Against' datatype='real' name='[scoreFlurryAdjustedTotalShotCreditAgainst]' role='measure' type='quantitative' />
      <column caption='Score Flurry Adjusted Total Shot Credit For' datatype='real' name='[scoreFlurryAdjustedTotalShotCreditFor]' role='measure' type='quantitative' />
      <column caption='Score Venue Adjustedx Goals Against' datatype='real' name='[scoreVenueAdjustedxGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='Score Venue Adjustedx Goals For' datatype='real' name='[scoreVenueAdjustedxGoalsFor]' role='measure' type='quantitative' />
      <column caption='Season' datatype='integer' name='[season]' role='measure' type='quantitative' />
      <column caption='Shot Attempts Against' datatype='real' name='[shotAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Shot Attempts For' datatype='real' name='[shotAttemptsFor]' role='measure' type='quantitative' />
      <column caption='Shots On Goal Against' datatype='real' name='[shotsOnGoalAgainst]' role='measure' type='quantitative' />
      <column caption='Shots On Goal For' datatype='real' name='[shotsOnGoalFor]' role='measure' type='quantitative' />
      <column caption='Situation' datatype='string' name='[situation]' role='dimension' type='nominal' />
      <column caption='Takeaways Against' datatype='real' name='[takeawaysAgainst]' role='measure' type='quantitative' />
      <column caption='Takeaways For' datatype='real' name='[takeawaysFor]' role='measure' type='quantitative' />
      <column caption='Team' datatype='string' name='[team]' role='dimension' type='nominal' />
      <column caption='Total Shot Credit Against' datatype='real' name='[totalShotCreditAgainst]' role='measure' type='quantitative' />
      <column caption='Total Shot Credit For' datatype='real' name='[totalShotCreditFor]' role='measure' type='quantitative' />
      <column caption='Unblocked Shot Attempts Against' datatype='real' name='[unblockedShotAttemptsAgainst]' role='measure' type='quantitative' />
      <column caption='Unblocked Shot Attempts For' datatype='real' name='[unblockedShotAttemptsFor]' role='measure' type='quantitative' />
      <column caption='X Freeze Against' datatype='real' name='[xFreezeAgainst]' role='measure' type='quantitative' />
      <column caption='X Freeze For' datatype='real' name='[xFreezeFor]' role='measure' type='quantitative' />
      <column caption='X Goals Against' datatype='real' name='[xGoalsAgainst]' role='measure' type='quantitative' />
      <column caption='X Goals For' datatype='real' name='[xGoalsFor]' role='measure' type='quantitative' />
      <column caption='X Goals From Actual Rebounds Of Shots Against' datatype='real' name='[xGoalsFromActualReboundsOfShotsAgainst]' role='measure' type='quantitative' />
      <column caption='X Goals From Actual Rebounds Of Shots For' datatype='real' name='[xGoalsFromActualReboundsOfShotsFor]' role='measure' type='quantitative' />
      <column caption='X Goals Fromx Rebounds Of Shots Against' datatype='real' name='[xGoalsFromxReboundsOfShotsAgainst]' role='measure' type='quantitative' />
      <column caption='X Goals Fromx Rebounds Of Shots For' datatype='real' name='[xGoalsFromxReboundsOfShotsFor]' role='measure' type='quantitative' />
      <column caption='X Goals Percentage' datatype='real' name='[xGoalsPercentage]' role='measure' type='quantitative' />
      <column caption='X On Goal Against' datatype='real' name='[xOnGoalAgainst]' role='measure' type='quantitative' />
      <column caption='X On Goal For' datatype='real' name='[xOnGoalFor]' role='measure' type='quantitative' />
      <column caption='X Play Continued In Zone Against' datatype='real' name='[xPlayContinuedInZoneAgainst]' role='measure' type='quantitative' />
      <column caption='X Play Continued In Zone For' datatype='real' name='[xPlayContinuedInZoneFor]' role='measure' type='quantitative' />
      <column caption='X Play Continued Outside Zone Against' datatype='real' name='[xPlayContinuedOutsideZoneAgainst]' role='measure' type='quantitative' />
      <column caption='X Play Continued Outside Zone For' datatype='real' name='[xPlayContinuedOutsideZoneFor]' role='measure' type='quantitative' />
      <column caption='X Play Stopped Against' datatype='real' name='[xPlayStoppedAgainst]' role='measure' type='quantitative' />
      <column caption='X Play Stopped For' datatype='real' name='[xPlayStoppedFor]' role='measure' type='quantitative' />
      <column caption='X Rebounds Against' datatype='real' name='[xReboundsAgainst]' role='measure' type='quantitative' />
      <column caption='X Rebounds For' datatype='real' name='[xReboundsFor]' role='measure' type='quantitative' />
      <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;Canada&quot;' />
      </semantic-values>
      <object-graph>
        <objects>
          <object caption='L.A.csv' id='L.A.csv_D5D4F205ACCE4DE0AACFCD152856004F'>
            <properties context=''>
              <relation connection='textscan.1hzm83v0hh3qx81e9epif1p6bs7f' name='L.A.csv' table='[L.A#csv]' type='table'>
                <columns character-set='UTF-8' header='yes' locale='en_CA' separator=','>
                  <column datatype='string' name='team' ordinal='0' />
                  <column datatype='integer' name='season' ordinal='1' />
                  <column datatype='string' name='name' ordinal='2' />
                  <column datatype='integer' name='gameId' ordinal='3' />
                  <column datatype='string' name='playerTeam' ordinal='4' />
                  <column datatype='string' name='opposingTeam' ordinal='5' />
                  <column datatype='string' name='home_or_away' ordinal='6' />
                  <column datatype='date' name='gameDate' ordinal='7' />
                  <column datatype='string' name='position' ordinal='8' />
                  <column datatype='string' name='situation' ordinal='9' />
                  <column datatype='real' name='xGoalsPercentage' ordinal='10' />
                  <column datatype='real' name='corsiPercentage' ordinal='11' />
                  <column datatype='real' name='fenwickPercentage' ordinal='12' />
                  <column datatype='real' name='iceTime' ordinal='13' />
                  <column datatype='real' name='xOnGoalFor' ordinal='14' />
                  <column datatype='real' name='xGoalsFor' ordinal='15' />
                  <column datatype='real' name='xReboundsFor' ordinal='16' />
                  <column datatype='real' name='xFreezeFor' ordinal='17' />
                  <column datatype='real' name='xPlayStoppedFor' ordinal='18' />
                  <column datatype='real' name='xPlayContinuedInZoneFor' ordinal='19' />
                  <column datatype='real' name='xPlayContinuedOutsideZoneFor' ordinal='20' />
                  <column datatype='real' name='flurryAdjustedxGoalsFor' ordinal='21' />
                  <column datatype='real' name='scoreVenueAdjustedxGoalsFor' ordinal='22' />
                  <column datatype='real' name='flurryScoreVenueAdjustedxGoalsFor' ordinal='23' />
                  <column datatype='real' name='shotsOnGoalFor' ordinal='24' />
                  <column datatype='real' name='missedShotsFor' ordinal='25' />
                  <column datatype='real' name='blockedShotAttemptsFor' ordinal='26' />
                  <column datatype='real' name='shotAttemptsFor' ordinal='27' />
                  <column datatype='real' name='goalsFor' ordinal='28' />
                  <column datatype='real' name='reboundsFor' ordinal='29' />
                  <column datatype='real' name='reboundGoalsFor' ordinal='30' />
                  <column datatype='real' name='freezeFor' ordinal='31' />
                  <column datatype='real' name='playStoppedFor' ordinal='32' />
                  <column datatype='real' name='playContinuedInZoneFor' ordinal='33' />
                  <column datatype='real' name='playContinuedOutsideZoneFor' ordinal='34' />
                  <column datatype='real' name='savedShotsOnGoalFor' ordinal='35' />
                  <column datatype='real' name='savedUnblockedShotAttemptsFor' ordinal='36' />
                  <column datatype='real' name='penaltiesFor' ordinal='37' />
                  <column datatype='real' name='penalityMinutesFor' ordinal='38' />
                  <column datatype='real' name='faceOffsWonFor' ordinal='39' />
                  <column datatype='real' name='hitsFor' ordinal='40' />
                  <column datatype='real' name='takeawaysFor' ordinal='41' />
                  <column datatype='real' name='giveawaysFor' ordinal='42' />
                  <column datatype='real' name='lowDangerShotsFor' ordinal='43' />
                  <column datatype='real' name='mediumDangerShotsFor' ordinal='44' />
                  <column datatype='real' name='highDangerShotsFor' ordinal='45' />
                  <column datatype='real' name='lowDangerxGoalsFor' ordinal='46' />
                  <column datatype='real' name='mediumDangerxGoalsFor' ordinal='47' />
                  <column datatype='real' name='highDangerxGoalsFor' ordinal='48' />
                  <column datatype='real' name='lowDangerGoalsFor' ordinal='49' />
                  <column datatype='real' name='mediumDangerGoalsFor' ordinal='50' />
                  <column datatype='real' name='highDangerGoalsFor' ordinal='51' />
                  <column datatype='real' name='scoreAdjustedShotsAttemptsFor' ordinal='52' />
                  <column datatype='real' name='unblockedShotAttemptsFor' ordinal='53' />
                  <column datatype='real' name='scoreAdjustedUnblockedShotAttemptsFor' ordinal='54' />
                  <column datatype='real' name='dZoneGiveawaysFor' ordinal='55' />
                  <column datatype='real' name='xGoalsFromxReboundsOfShotsFor' ordinal='56' />
                  <column datatype='real' name='xGoalsFromActualReboundsOfShotsFor' ordinal='57' />
                  <column datatype='real' name='reboundxGoalsFor' ordinal='58' />
                  <column datatype='real' name='totalShotCreditFor' ordinal='59' />
                  <column datatype='real' name='scoreAdjustedTotalShotCreditFor' ordinal='60' />
                  <column datatype='real' name='scoreFlurryAdjustedTotalShotCreditFor' ordinal='61' />
                  <column datatype='real' name='xOnGoalAgainst' ordinal='62' />
                  <column datatype='real' name='xGoalsAgainst' ordinal='63' />
                  <column datatype='real' name='xReboundsAgainst' ordinal='64' />
                  <column datatype='real' name='xFreezeAgainst' ordinal='65' />
                  <column datatype='real' name='xPlayStoppedAgainst' ordinal='66' />
                  <column datatype='real' name='xPlayContinuedInZoneAgainst' ordinal='67' />
                  <column datatype='real' name='xPlayContinuedOutsideZoneAgainst' ordinal='68' />
                  <column datatype='real' name='flurryAdjustedxGoalsAgainst' ordinal='69' />
                  <column datatype='real' name='scoreVenueAdjustedxGoalsAgainst' ordinal='70' />
                  <column datatype='real' name='flurryScoreVenueAdjustedxGoalsAgainst' ordinal='71' />
                  <column datatype='real' name='shotsOnGoalAgainst' ordinal='72' />
                  <column datatype='real' name='missedShotsAgainst' ordinal='73' />
                  <column datatype='real' name='blockedShotAttemptsAgainst' ordinal='74' />
                  <column datatype='real' name='shotAttemptsAgainst' ordinal='75' />
                  <column datatype='real' name='goalsAgainst' ordinal='76' />
                  <column datatype='real' name='reboundsAgainst' ordinal='77' />
                  <column datatype='real' name='reboundGoalsAgainst' ordinal='78' />
                  <column datatype='real' name='freezeAgainst' ordinal='79' />
                  <column datatype='real' name='playStoppedAgainst' ordinal='80' />
                  <column datatype='real' name='playContinuedInZoneAgainst' ordinal='81' />
                  <column datatype='real' name='playContinuedOutsideZoneAgainst' ordinal='82' />
                  <column datatype='real' name='savedShotsOnGoalAgainst' ordinal='83' />
                  <column datatype='real' name='savedUnblockedShotAttemptsAgainst' ordinal='84' />
                  <column datatype='real' name='penaltiesAgainst' ordinal='85' />
                  <column datatype='real' name='penalityMinutesAgainst' ordinal='86' />
                  <column datatype='real' name='faceOffsWonAgainst' ordinal='87' />
                  <column datatype='real' name='hitsAgainst' ordinal='88' />
                  <column datatype='real' name='takeawaysAgainst' ordinal='89' />
                  <column datatype='real' name='giveawaysAgainst' ordinal='90' />
                  <column datatype='real' name='lowDangerShotsAgainst' ordinal='91' />
                  <column datatype='real' name='mediumDangerShotsAgainst' ordinal='92' />
                  <column datatype='real' name='highDangerShotsAgainst' ordinal='93' />
                  <column datatype='real' name='lowDangerxGoalsAgainst' ordinal='94' />
                  <column datatype='real' name='mediumDangerxGoalsAgainst' ordinal='95' />
                  <column datatype='real' name='highDangerxGoalsAgainst' ordinal='96' />
                  <column datatype='real' name='lowDangerGoalsAgainst' ordinal='97' />
                  <column datatype='real' name='mediumDangerGoalsAgainst' ordinal='98' />
                  <column datatype='real' name='highDangerGoalsAgainst' ordinal='99' />
                  <column datatype='real' name='scoreAdjustedShotsAttemptsAgainst' ordinal='100' />
                  <column datatype='real' name='unblockedShotAttemptsAgainst' ordinal='101' />
                  <column datatype='real' name='scoreAdjustedUnblockedShotAttemptsAgainst' ordinal='102' />
                  <column datatype='real' name='dZoneGiveawaysAgainst' ordinal='103' />
                  <column datatype='real' name='xGoalsFromxReboundsOfShotsAgainst' ordinal='104' />
                  <column datatype='real' name='xGoalsFromActualReboundsOfShotsAgainst' ordinal='105' />
                  <column datatype='real' name='reboundxGoalsAgainst' ordinal='106' />
                  <column datatype='real' name='totalShotCreditAgainst' ordinal='107' />
                  <column datatype='real' name='scoreAdjustedTotalShotCreditAgainst' ordinal='108' />
                  <column datatype='real' name='scoreFlurryAdjustedTotalShotCreditAgainst' ordinal='109' />
                </columns>
              </relation>
            </properties>
          </object>
        </objects>
      </object-graph>
    </datasource>
  </datasources>
  <worksheets>
    <worksheet name='Sheet 1'>
      <layout-options>
        <title>
          <formatted-text>
            <run>LA Kings Goals For </run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='L.A.csv (Multiple Connections)' name='federated.014yrua12d58ti17ud8qi1s9fkgl' />
          </datasources>
          <datasource-dependencies datasource='federated.014yrua12d58ti17ud8qi1s9fkgl'>
            <column caption='Goals For' datatype='real' name='[goalsFor]' role='measure' type='quantitative' />
            <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
            <column-instance column='[home_or_away]' derivation='None' name='[none:home_or_away:nk]' pivot='key' type='nominal' />
            <column-instance column='[goalsFor]' derivation='Sum' name='[sum:goalsFor:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <shelf-sorts>
            <shelf-sort-v2 dimension-to-sort='[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]' direction='DESC' is-on-innermost-dimension='true' measure-to-sort-by='[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:goalsFor:qk]' shelf='rows' />
          </shelf-sorts>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</rows>
        <cols>[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:goalsFor:qk]</cols>
      </table>
      <simple-id uuid='{B086C280-68DA-40EA-82A3-631395B01CFC}' />
    </worksheet>
    <worksheet name='Sheet 2'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Goals Against </run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='L.A.csv (Multiple Connections)' name='federated.014yrua12d58ti17ud8qi1s9fkgl' />
          </datasources>
          <datasource-dependencies datasource='federated.014yrua12d58ti17ud8qi1s9fkgl'>
            <column caption='Goals Against' datatype='real' name='[goalsAgainst]' role='measure' type='quantitative' />
            <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
            <column-instance column='[home_or_away]' derivation='None' name='[none:home_or_away:nk]' pivot='key' type='nominal' />
            <column-instance column='[goalsAgainst]' derivation='Sum' name='[sum:goalsAgainst:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <shelf-sorts>
            <shelf-sort-v2 dimension-to-sort='[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]' direction='DESC' is-on-innermost-dimension='true' measure-to-sort-by='[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:goalsAgainst:qk]' shelf='rows' />
          </shelf-sorts>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</rows>
        <cols>[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:goalsAgainst:qk]</cols>
      </table>
      <simple-id uuid='{7EC87A56-E4E9-4E95-8C65-753108381A63}' />
    </worksheet>
    <worksheet name='Sheet 3'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Penalties Taken </run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='L.A.csv (Multiple Connections)' name='federated.014yrua12d58ti17ud8qi1s9fkgl' />
          </datasources>
          <datasource-dependencies datasource='federated.014yrua12d58ti17ud8qi1s9fkgl'>
            <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
            <column-instance column='[home_or_away]' derivation='None' name='[none:home_or_away:nk]' pivot='key' type='nominal' />
            <column caption='Penalties For' datatype='real' name='[penaltiesFor]' role='measure' type='quantitative' />
            <column-instance column='[penaltiesFor]' derivation='Sum' name='[sum:penaltiesFor:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='false' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</rows>
        <cols>[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:penaltiesFor:qk]</cols>
      </table>
      <simple-id uuid='{7D1E2B8F-FE9E-42B3-ACAC-F1172F1268B0}' />
    </worksheet>
    <worksheet name='Sheet 4'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Giveaways</run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='L.A.csv (Multiple Connections)' name='federated.014yrua12d58ti17ud8qi1s9fkgl' />
          </datasources>
          <datasource-dependencies datasource='federated.014yrua12d58ti17ud8qi1s9fkgl'>
            <column caption='Giveaways Against' datatype='real' name='[giveawaysAgainst]' role='measure' type='quantitative' />
            <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
            <column-instance column='[home_or_away]' derivation='None' name='[none:home_or_away:nk]' pivot='key' type='nominal' />
            <column-instance column='[giveawaysAgainst]' derivation='Sum' name='[sum:giveawaysAgainst:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</rows>
        <cols>[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:giveawaysAgainst:qk]</cols>
      </table>
      <simple-id uuid='{D528EF9F-EB64-4C72-8CAC-3AF17EAF54CC}' />
    </worksheet>
    <worksheet name='Sheet 5'>
      <layout-options>
        <title>
          <formatted-text>
            <run>Takeaways Against </run>
          </formatted-text>
        </title>
      </layout-options>
      <table>
        <view>
          <datasources>
            <datasource caption='L.A.csv (Multiple Connections)' name='federated.014yrua12d58ti17ud8qi1s9fkgl' />
          </datasources>
          <datasource-dependencies datasource='federated.014yrua12d58ti17ud8qi1s9fkgl'>
            <column caption='Home Or Away' datatype='string' name='[home_or_away]' role='dimension' type='nominal' />
            <column-instance column='[home_or_away]' derivation='None' name='[none:home_or_away:nk]' pivot='key' type='nominal' />
            <column-instance column='[takeawaysAgainst]' derivation='Sum' name='[sum:takeawaysAgainst:qk]' pivot='key' type='quantitative' />
            <column caption='Takeaways Against' datatype='real' name='[takeawaysAgainst]' role='measure' type='quantitative' />
          </datasource-dependencies>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
          </pane>
        </panes>
        <rows>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</rows>
        <cols>[federated.014yrua12d58ti17ud8qi1s9fkgl].[sum:takeawaysAgainst:qk]</cols>
      </table>
      <simple-id uuid='{94BBC98C-7F1D-4602-B0F5-26F278B4382F}' />
    </worksheet>
  </worksheets>
  <windows source-height='30'>
    <window class='worksheet' name='Sheet 1'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away (TOR.csv):nk]</field>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{41EDD24A-C3A9-431C-9F2B-376F5CCD68C4}' />
    </window>
    <window class='worksheet' name='Sheet 2'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{6287C30E-D801-4A23-B8EF-829F89118C61}' />
    </window>
    <window class='worksheet' name='Sheet 3'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{C197EBDF-D2E4-4DDA-B54F-D9A123E95BEF}' />
    </window>
    <window class='worksheet' name='Sheet 4'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{0103D82B-E58F-4607-87DE-2D2BD6507380}' />
    </window>
    <window class='worksheet' maximized='true' name='Sheet 5'>
      <cards>
        <edge name='left'>
          <strip size='160'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[federated.014yrua12d58ti17ud8qi1s9fkgl].[none:home_or_away:nk]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{0DF3FE17-704C-492C-B8A7-CA5521096FEB}' />
    </window>
  </windows>
  <thumbnails>
    <thumbnail height='238' name='Sheet 1' width='384'>
      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
      vV4Aw0MA+IAxY8b0++9Q628XERGhF198Ubt379bx48d1+PDhfu1xcXH69re/raSkJLfLBwQE
      yGazuV1/aGioHnzwQZWXlysvL08BAQNPHj31y/V+fX296uvrPW7XUGYlAbh7bNZQpo1g1Onp
      6dG5c+d09uzZvj8I83mmbI4WTqdTa/7v7ZHuBjAqcQbgp8aMGaOpU6dq6tSpI90VAD6Km8AA
      YCgCAAAMRQAAgKEIAAAwFLOAMKo5nU45HI6R7oZfam1tlXRzCjDuPl8YX84AAMBQBAAAGIoA
      AABDEQAAYCgCAAAMRQAAgKEIAAAwFAEAAIYiAADAUHwdNEa9J3/6xkh3ARiVOAMAAEMRAABg
      KAIAAAxFAACAoQgAADAUs4B8kGVZ2rt3r7q7uxUcHKwvfelLHmsbGhp08eJFJSYmauLEiR7r
      ysvL1dXVpcjISE2ZMsVjXU1Nja5fv67p06fLZrO5ramurlZ5ebkkKScnR4mJiW7rWlpaVFNT
      o+DgYGVmZnr8TJcTJ05IktfPBnD3EAA+qK6uTu+8807fzzk5OYqNjXVbW1NTo927d+uJJ57Q
      ihUr3Na0trbqpZdekmVZSkpK0k9+8hOPn71z5061t7dr69atHnfCBw4c0MmTJyVJjY2N2rBh
      g9s6u92uXbt2yel06mc/+5kSEhI8fm5ZWZm2bdum5ORkzZgxw2MdgLuHS0A+qKioSJK0YMEC
      SVJhYaHH2oyMDEk3j8o9qaqqkmVZGjt2rOrr69XR0eG27sqVK2pqalJqaqoCAtz/r3H9+nVV
      VFQoPT1dMTExOnHihLq6utzWOhwOLVu2TJZl6R//+IfH/t3avmrVKo91AO4uAsDHWJaloqIi
      hYWFaeXKlbLb7V4DICYmRhMnTlR9fb1u3LjhtqaqqkqStGTJEvX29ur06dNu61whkp6e7vHz
      SkpK1Nvbq7y8POXm5qqzs1NlZWUe6xctWqSYmBidPHmyrx+3+/jjj9XQ0KCcnBylpKR4XBeA
      u4sA8DF1dXVqamrSzJkzFRwcrKysLDU0NOjChQsel8nIyFBPT49qamrctldWVio2NlaPPPJI
      38/uuILBdVbhTmFhoWw2m2bOnKnc3FxJ/ztjccdut/ddmvr73/+u2/8EdVdXl95++22NGTNG
      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
    </thumbnail>
    <thumbnail height='238' name='Sheet 2' width='384'>
      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
      lN1uV2Vlpex2uzIzM3vVOp1O7du3T1VVVSooKOh39k9LS4uqq6tlt9u1ffv2Pu3emT3l5eXy
      eDwKDw/3u52RkZF69NFHtWvXLj3xxBN+6wDcfQRAEPDe/JWu3Qeora31W1tSUqJFixb5bMvJ
      ydHevXv15ZdfKiMjQ9XV1UpLS+uzQ/bu6AcaAN6bv93d3frvf//rt2/t7e06cuRIv0f13v6M
      GDEiYB2Au4sACAInTpxQU1OTHnrooT7X/6/35ptvqrKyUi6Xy+dZgDcAqqurNWLECF29etXn
      Z/DEx8crMTGx50ZwdXW1HA6H349q8J6drF271u/nDdXV1ek3v/mNSkpKuKwDDBHcAwgC3h3s
      jBkzFBER4fdffzNurr8P4O/6v5fT6dS5c+d0+vRpuVwuv9f/vZd/Jk6cqOTkZL99czqdio2N
      1ZEjR+TxeG57TADcfQTAIPNe/vHe6A1k+vTpCgsL8zvbJiYmRikpKaqtrdXRo0cVHh6utLQ0
      n7XesNixY4csy+r38o83fPzxPh3c0dHR86meAIIbATDITpw4ocuXL2vq1Kmy2wNfkfM+IHb2
      7FmdOnXKZ01OTo48Hk/PE7vDhg3zWydd28Ff//uNvGcbvmb/3GggHw0BIHgQAIPs0KFDktTv
      EbaXt87fUfb1O/JAZxQjR45UcnKyLMtSVFSUxo4d26emtbVV1dXVSk1N1ejRo/vtW2ZmpkaO
      HKny8vKep30BBC+bdeOncwFDiNvt1vLXP+q/EEAfnAEAgKEIAAAwFAEAAIYiAADAUAQAABiK
      WUAY0txutxwOx2B3I6R5PzU2JiZmkHsSmgZzfDkDAABDEQAAYCgCAAAMRQAAgKEIAAAwFAEA
      AIYiAADAUAQAABiKAAAAQ/Gl8Bjynvm/rYPdBWBI4gwAAAxFAACAoQgAADAUAQAAhiIAAMBQ
      zAIKAi6XS+fOnVN2draioqL81lmWpcOHDys6OloZGRl+69xut06cOKHa2lp99dVXiouLU1pa
      mjIyMnTffff5Xa67u1uHDh3q+T0nJ2dAn7V/6dIlnTx5UpIUGRkpp9Ppc/v6M2LECE2ePLnf
      OgB3BgEQBIqKirR792799Kc/VVZWlt+6trY2bdy4UZMmTdIrr7zis6a+vl4bN25UU1NTr9cL
      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
      AICh/h/zrbyA6scdjwAAAABJRU5ErkJggg==
    </thumbnail>
    <thumbnail height='238' name='Sheet 3' width='384'>
      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
      kSNH1NHRoTVr1ugrX/lKVM3Xxs3LMG+//bb8fr9SUlI0f/585ebmKj4+XufPn5fH49Hg4KBW
      r16tr33tayPWH+9+MTg4qO3bt6uqqkqZmZlatWqVpk+frtraWh0/flxJSUnBN5RGGwIAMamh
      oUFvvvnmsNkbTqdT69ev1zPPPMPBP0p1dnbqvffe07Fjx9Td3T2sLSkpSU8++aTWrFlj+1bO
      8e4XQ0ND+u1vf6uPPvpItx4y09PT9dJLL0Xl2b9EACCGWZallpYWNTc3a8aMGSooKBj1YSBE
      j+7ubrW0tKivr0+zZ89Wenr6mIL9bvaLnp4enTlzRj6fT/n5+crMzLzbrzGpCAAAMBQ3gQHA
      UAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACGIgAAwFAEAAAYigAAAEMRAABgKAIA
      AAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgCAAAMRQAAgKEIAAAwFAEAAIYi
      AADAUAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACGIgAAwFAEAAAYigAAAEMRAABg
      KAIAAAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgCAAAMRQAAgKEIAAAwFAEA
      AIYiAADAUAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACGIgAAwFAEAAAYigAAAEMR
      AABgqP8ChQe4SKRd+RcAAAAASUVORK5CYII=
    </thumbnail>
    <thumbnail height='238' name='Sheet 4' width='384'>
      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
      gg==
    </thumbnail>
    <thumbnail height='238' name='Sheet 5' width='384'>
      iVBORw0KGgoAAAANSUhEUgAAAYAAAADuCAYAAAAwTtAhAAAACXBIWXMAAA7DAAAOwwHHb6hk
      AAAVOklEQVR4nO3df0xV9/3H8de9XOWHoICAAwXll1ylrQpS2244FzXTNbbprEvN0nZzdkmz
      bN2SpdkW/1iaNlmWLN2S2tnZxGVznVuyplU3dHNuxc3iAJVfCigg1YL4AxD08uNe7/n+Ye79
      qtxzoR0MuJ/nIzHNvZ/3Oedzm5PzOp/zOefgsCzLEgDAOM7J7gAAYHIQAABgKAIAAAxFAACA
      oQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgCAAAMRQAAgKEIAAAwFAEAAIYiAADAUAQA
      ABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACGIgAAwFAEAAAYigAAAEMRAABgKAIAAAxF
      AACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgCAAAMRQAAgKEIAAAwFAEAAIYiAADA
      UAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACGIgAAwFAEAAAYigAAAEMRAABgKAIA
      AAxFAACAoQgAADAUAQAAhiIAAMBQBACmNY/HM9ldQITp7+9Xf3//ZHfjf4IAAABDEQAAYCgC
      AAAMRQAAgKEIAAAwlGuyOwD8t5780b7J7gIwLTECAABDEQAAYCgCAAAMRQAAgKEIAAAwFHcB
      TUGWZenAgQPy+XyKjY3Vxo0bbWs7OjrU1dWlRYsWKSkpybauvr5eXq9Xc+fOVVZWlm1dS0uL
      bt26pQcffFAOhyNkTXNzs+rr6yVJRUVFWrRoUci6vr4+tbS0KDY2Vm6323abAbW1tZIUdtsA
      xg8BMAW1tbXpz3/+c/BzUVGR5s2bF7K2paVFe/fu1YYNG/TUU0+FrOnv79cbb7why7KUnZ2t
      H/zgB7bb3r17twYGBvT666/bHoQPHTqkhoYGSVJ3d7e2b98ess7lcum3v/2tPB6PduzYoQUL
      Fthut66uTjt37lROTo4eeugh2zoA44dLQFNQdXW1JKm0tFSSVFVVZVtbUFAg6c5ZuZ2mpiZZ
      lqUZM2aovb1dg4ODIeuuXbumnp4e5eXlyekMvWvcunVLZ8+e1eLFi5WWlqba2lp5vd6QtXFx
      cXr88cdlWZbeffdd2/7d3f7000/b1gEYXwTAFGNZlqqrqzVnzhxt3rxZLpcrbACkpaUpKSlJ
      7e3tGh4eDlnT1NQkSfrCF74gv9+vc+fOhawLhMjixYttt3f69Gn5/X6tXLlSxcXFGhoaUl1d
      nW395z//eaWlpamhoSHYj/t9+OGH6ujoUFFRkXJzc23XBWB8EQBTTFtbm3p6erRixQrFxsaq
      sLBQHR0d6uzstF2moKBAt2/fVktLS8j2xsZGzZs3T48++mjwcyiBYAiMKkKpqqqSw+HQihUr
      VFxcLOn/RyyhuFyu4KWpP/3pT7Is6552r9er/fv3KyoqSl/+8pdt1wNg/BEAU0zgbD9wcC0q
      KpIU/iAb7jJQd3e3rly5IrfbrfT0dCUkJNieiTc3NysmJsZ2kvjmzZtqbGxUfn6+Zs+erczM
      TKWmpqqurs529BH4Dbm5uWpvbx/xO44ePaqenh6tWbNGqamptusAMP4IgCnEsiydPHlSCQkJ
      ys/PlyQtW7ZMLpdrTAEQ6tJO4Gzf7XbL4XCooKBAly5dGvGXtHp6enTt2jXl5+fbXv8/deqU
      /H5/MJSkOwf3oaGh4F1BdrZs2SKHw6H33ntPt2/flnTnr3kdOnQoOFcA4H+LAJhCWltbg5d/
      AnfgxMbGasmSJWEvA82dO1cpKSlqa2sbMSHb2NgYPPBLd4LAsqwRo4BAeIS7/l9dXS2Hw3FP
      AARGKuHmKSQpOztbK1eu1NWrV1VeXi5JKisrk8fj0Ze+9CXNmjUr7PIAxh8BMEVYlqVf/epX
      io+P19atW+9p27Ztm6KiovTWW2/ZLv/EE0/I5/Pp8OHDwe8uX76sEydOaP369cEDbGlpqZKS
      krR///57lj948KBiY2O1fv36kOs/duyYzp49qy1btmjOnDnB7xcuXKj169eruro67ChFkrZv
      364vfvGL2rdvn7797W/rr3/9q1544QXbbQKYWATAFNHS0qLe3l4tX758xCWYuLg4ud1udXZ2
      qqOjI+TyoeYB7r78c39tR0dH8A9f9/X1qaurS/n5+bb3/gcmf+8++w8IfDfaKECSNm7cqPj4
      eA0PDwdHBQAmBw+CTRGBs+eOjg795je/GdF+9erVYF1GRsaI9sTERM2bN0+tra3y+XxyuVxq
      bGyUy+VSXl7ePbVut1sVFRVqamrSypUrR737p7+/X83NzXK5XDpw4MCI9sCdPfX19RoaGlJ0
      dLTt74yNjdVnP/tZHT58WOvWrbOtAzDxCIApIDD5K92ZB2htbbWtra6u1qZNm0K2FRQUqLy8
      XBcuXFBubq6am5uVnZ094oAcONCPNQACk79+v1///ve/bfs2PDysurq6Uc/qA/2ZOXNm2DoA
      E4sAmALOnz+v3t5ePfLIIyOu/9/tl7/8pRobG9XR0RFyFBAIgObmZs2cOVO3bt0K+Q6e5ORk
      paamBieCm5ubFRcXZ/uqhsDo5Mc//rHt+4ba2tr085//XNXV1VzWAaYJ5gCmgMABtqSkRDEx
      Mbb/Rrvj5u55ALvr/wFut1tdXV36+OOP1dHRYXv9P3D5Z9GiRUpPT7ftm9vtVmJiourq6jQ0
      NPRf/z8BMPEIgEkWuPwTmOgNZ8WKFXI6nbZ32yQkJCgjI0Otra1qaGhQdHS0srOzQ9YGwuLg
      wYOyLGvUyz+B8LETeDrY6/UG3+oJYGojACbZ+fPndePGDT300ENyucJfkQs8IHb58mVdunQp
      ZE1BQYGGhoaCT+xGRUXZ1kl3DvB3f75fYLQR6u6f+43l1RAApg4CYJLV1NRI0qhn2AGBOruz
      7LsP5OFGFLNnz1Z6erosy9KsWbM0f/78ETUDAwNqbm5WVlaWUlJSRu1bXl6eZs+erfr6+uDT
      vgCmLod1/9u5gGnE4/Fo66v7Ry8EMAIjAAAwFAEAAIYiAADAUAQAABiKAAAAQ3EXEKY1j8ej
      uLi4ye4GIkjgLbkJCQmT3JOJxwgAAAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAA
      YCgCAAAMxR+Fx7T35I/2TXYXgGmJEQAAGIoAAABDEQAAYCgCAAAMRQAAgKG4C2gK6OjoUFdX
      lxYvXqxZs2bZ1lmWpdraWsXHxys3N9e2zuPx6Pz582ptbdXFixeVlJSk7Oxs5ebm6jOf+Yzt
      cn6/XzU1NcHPBQUFY3rX/vXr1/XRRx9JkmJjY+V2u0P+vtHMnDlThYWFo9YBGB8EwBRw/Phx
      /e1vf9P3v/995efn29YNDg7qzTff1JIlS/Td7343ZE17e7vefPNN9fb23vP9sWPHJEmbNm3S
      448/LofDMWJZr9erXbt2BT9v2bJF69atG7X/Bw8e1PHjxyVJcXFxev3110P+vtEkJSXpJz/5
      yah1AMYHARBBampqtHv3bnm9Xq1evVrFxcXKzs7W9evXde7cOb3//vs6cOCALl++rG984xsh
      Q0CSUlNT1dvbq8rKylEDwOfz6fTp00pKSpLf75fX67Wt3bRpk9LS0mzbo6Ojx/ZDAYwLAiBC
      +Hw+vfPOO/L5fNq6davWrFkTbMvIyFBGRobcbrd+8YtfqLKyUiUlJVq2bFnIdaWnpysrK0vV
      1dW6cuVK2IP2mTNn5PF4tHr1atXW1o4Yedxt6dKlysnJ+dS/EcD4YhI4Qhw/fly9vb169NFH
      7zn4323evHn62te+Jkn6y1/+EnZ9q1atkiRVVVWFrQu0B+oBTB8EQIQ4cuSIJGnt2rVh6xYv
      XqysrCxduHBBra2ttnWFhYWKi4vTf/7zH9sar9ermpoazZ8/XxkZGZ+u4wAmDQEQAXw+n65c
      uaKFCxdqwYIFo9Y/9thjkqSPP/7Ytsblcqm4uFidnZ26dOlSyJr6+noNDg5y9g9MUwRABOju
      7pZlWUpNTR1TfeCa/vXr18PWPfzww5KkysrKkO1VVVVyOBwqKSn5BL0FMFUwCTyFHD16VCdP
      nrRt9/l8Ib+/du2aJCk5OXlM2wnUBZazk5+fr6SkJFVWVuqpp566p21oaEi1tbXKy8sb83bL
      ysqUkpISdntFRUVjWheA/x4BMIUsW7Ys7HMAAwMDKi8vH/F94PbJ4eHhMW0nUDdz5sywdQ6H
      Q9/61rf06quvat++fXrmmWeCbXv27NHt27f14osvjmmbklRaWqqsrCzb9tH6A2B8EQBTyNy5
      czV37lzb9oGBAdvlJKmnp2dM2+nu7paksGfjAZmZmUpPT1d1dbW+8pWvyOl0anBwUPX19Sos
      LAz75PL94uPjlZiYOOZ6ABOLOYAIMGfOHLlcLl28eFGWZY1aH3htQ7iwudvDDz+svr4+NTU1
      SbrzwJnX6w3OEQCYngiACOBwOJSfn6/u7m6dPn06bK3X69WxY8fkdDqVl5c3pvXfPxlcVVWl
      6Oho2wfJAEwPBECE2LBhgyTp8OHD8vv9tnX/+te/1N/fr5KSkjGPAFJSUpSTk6NTp06pr69P
      Z86c0fLly7lmD0xzBECEcLvdysnJUVtbm9544w0NDQ2NqDl27Jj++Mc/yuFwBANjrFatWiWP
      x6O9e/fK5/Nx7z8QAZgEjiAvvPCCdu7cqYaGBr3yyit68MEHlZmZqRs3bqi5uVlnz57VjBkz
      9Nxzz33iJ3eLi4v1hz/8QTU1NUpISNCSJUs+cf/27dsXdhI4Pj5ezz333CdeL4BPhwCYAqKi
      ou7571jr75ecnKyXX35Ze/fu1alTp/SPf/zjnvb09HQ9//zzys7ODrm80+mUw+EIuf6EhAQt
      XbpU9fX1WrlypZzOkYNHu34Fvm9vb1d7e7vt7xrLXUkAxo/DGsttI5h2bt++rUuXLumjjz4K
      /kGYT3LL5nTh8Xi09dX9k90NYFpiBBChoqKitHDhQi1cuHCyuwJgimISGAAMRQAAgKEIAAAw
      FAEAAIbiLiBMax6PR3FxcZPdDUSQ/v5+SXdufY50jAAAwFAEAAAYiktAmNY8Hs9kdwGYthgB
      AIChGAEAgKEYAWBa83g8XAbCuDNlvyIAAMBQBAAAGIoAAABDEQAAYCgCAAAMRQAAgKEIAAAw
      FAEAAIYiAADAULwKAgAMxQgAAAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgC
      AAAMRQAAgKEIAAAwlGuyOwBMpHPnzqmpqUltbW1KTk7W4sWL9cADDyg2NnZErd/vV01NjVJS
      UpSZmWm7zvb2dnV3dyszM1MpKSkT2X1MkM7OTlVVVWnVqlVKS0sLWWPC/kAAIGK99957Kisr
      u+e78vJyZWRk6Hvf+55mz559T5vX69WuXbtUWFio73znOyHX2dXVpZ/97Gfy+/364Q9/OGF9
      x8To7u7WgQMHVFFRIb/fr3nz5tkGgAn7AwGAiPT++++rrKxMiYmJ+upXv6qCggJdvXpVhw4d
      UmVlpX76059qx44diomJGfM6fT6fdu/eraGhIW3dulXz58+fwF+A8dTf36+ysjJ98MEH8vl8
      47LOSNgfCABEnIGBAf39739XXFycXnrpJWVkZEiSFixYoG3btml4eFg1NTWqqKjQmjVrxrze
      d999VxcvXtSyZcs+0XKYXNevX9crr7yiwcFBJSQkaOPGjYqKitLvf/97ORyOT73eSNgfmARG
      xKmoqNDQ0JBKS0uDB/8Ap9OpLVu2SJI++OCDMa+zvr5eR48eVWJiop5//vlx7S8m1vDwsJxO
      p5588km99tprWrt2rVyu/+7cN1L2B0YAiDiVlZWSpEceeSRke2pqqnJzc9XS0qLOzk6lp6eH
      XV9fX59+/etfS5K2bdumWbNmjWt/MbFSUlL02muvKS4ublzWF0n7AyMARJzu7m4lJSWNOPu/
      2wMPPBCsDceyLO3Zs0f9/f3asGGDCgoKxrWvmHgzZswYt4N/pO0PBAAiimVZ6uvr05w5c8LW
      Bdp7e3vD1h05ckRnzpxRdna2nnjiiXHrJ6anSNsfuASEiHLz5k3dvn17xC2e90tISJAk3bhx
      Y0TbhQsX9Lvf/U6WZenDDz9UTEyMtm/fLqeT8yUTRfL+QAAgogwNDUmSoqOjw9YF2gcHB0e0
      3bp1S+Xl5cHPS5cunXYP+GD8RPL+QAAgogTO7G/evBm2LtAeaqSQk5OjZ555Rj6fT2+99ZZq
      a2t1/PhxPfbYY+PfYUx5kbw/TP8xDHCX6OhoxcTEqK+vL2xdoD3UXEFsbKwWLlyo3NxcffOb
      31RUVJTeeecdXbx4cUL6jKktkvcHAgARZ86cOeru7pbf77etuXbtWrA2nLy8PG3evDn4WgCP
      xzOufcX0Emn7AwGAiDN//nwNDAyooaEhZLtlWaqurpbT6Rz1GQBJWrt2rUpKSnTt2jXt2bNH
      lmWNd5cxjUTS/kAAIOKUlpZKko4fPx6yvbGxUT09PVq+fHlwzmA0zz77rDIyMlRbWzviBXMw
      T6TsDwQAIs6SJUuUmpqqkydP6p///Oc9bdevXw8+xbl69eoxrzM6OlovvviiYmJitH//fp05
      c2Yce4zpJlL2B+4CQsRxOBx69tlntXPnTu3bt0+tra3Ky8tTd3e3Kioq1Nvbq8997nNyu92f
      aL1paWn6+te/rl27duntt9/Wjh07lJycPEG/AuPlyJEjunz58j3fBT4fPXpUTU1Nwe9jY2O1
      efPmMa03EvYHAgARqaCgQC+99JJ27dqlEydO6MSJE5LuvAxu3bp1evrpp0e8CdLpdI76dsjl
      y5drw4YNKisr09tvv62XX355wn4Dxkd9fb3Onj0bsq21tVWtra3Bz4mJicEAMGF/cFjTeQYD
      GIVlWers7FR7e7sSExOVk5Mz6kNigCkIAAAwFJPAAGAoAgAADEUAAIChCAAAMBQBAACGIgAA
      wFAEAAAYigAAAEMRAABgKAIAAAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAAYCgC
      AAAMRQAAgKEIAAAwFAEAAIYiAADAUAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQBAACG
      IgAAwFAEAAAYigAAAEMRAABgKAIAAAxFAACAoQgAADAUAQAAhiIAAMBQBAAAGIoAAABDEQAA
      YCgCAAAMRQAAgKEIAAAwFAEAAIYiAADAUAQAABiKAAAAQxEAAGAoAgAADEUAAIChCAAAMBQB
      AACGIgAAwFAEAAAYigAAAEMRAABgKAIAAAxFAACAoQgAADDU/wEbkxA2kFAo2wAAAABJRU5E
      rkJggg==
    </thumbnail>
  </thumbnails>
</workbook>
