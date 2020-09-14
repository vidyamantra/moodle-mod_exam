# CHANGE HISTORY
## TODO
(27 errors/55 warnings) => phplint (0/0), phpcs (0/0), js (185/234), css (1/0), phpdoc (3/0), savepoint (0/0), thirdparty (0/0), grunt (1/1), shifter (0/0), mustache (0/0), 

## 14 sept version 2020091405
Variable "attempted_attempt" must not contain underscores.
$plugin->version   = 2020091407

## 14 sept version 2020091401
* 8 error(es) y 0 advertencia(s)
mod\exam\backup\moodle2\backup_exam_settingslib.php

    #1: <?php

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.
    End of line character is invalid; expected "\n" but found "\r\n"

mod\exam\db\caches.php

    #26: $definitions·=·array(

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.

mod\exam\lib.php

    #67: ········default:························return·null;

    Closing brace must be on a line by itself

mod\exam\view.php

    #93: $attempted_attempt·=·exam_user_attempts($exam->id,·$USER->id);

    Variable "attempted_attempt" must not contain underscores.

    #99: $output·.=·html_writer::tag('p',·get_string('attempted',·'exam',·$attempted_attempt));

    Variable "attempted_attempt" must not contain underscores.

    #105: if·(($exam->attempts·==·0)·||·$attempted_attempt·<·$exam->attempts)·{

    Variable "attempted_attempt" must not contain underscores.

    #107: ····if·($attempted_attempt·>·0)·{

    Variable "attempted_attempt" must not contain underscores.

## 14 sept version 20200914
* 17 error(es) y 55 advertencia(s)

mod\exam\backup\moodle2\backup_exam_settingslib.php

    #1: <?php

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.
    End of line character is invalid; expected "\n" but found "\r\n"

mod\exam\db\caches.php

    #26: $definitions·=·array(

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.

mod\exam\lib.php

    #46: ········case·FEATURE_GRADE_HAS_GRADE:···return·true;

    Closing brace must be on a line by itself

    #47: ········case·FEATURE_GRADE_OUTCOMES:····return·true;

    Closing brace must be on a line by itself

    #48: ········case·FEATURE_GROUPS:············return·true;

    Closing brace must be on a line by itself

    #49: ········case·FEATURE_GROUPINGS:·········return·true;

    Closing brace must be on a line by itself

    #50: ········case·FEATURE_GROUPMEMBERSONLY:··return·true;

    Closing brace must be on a line by itself

    #51: ········case·FEATURE_MOD_INTRO:·········return·true;

    Closing brace must be on a line by itself

    #52: ········case·FEATURE_BACKUP_MOODLE2:····return·true;

    Closing brace must be on a line by itself

    #55: ········case·FEATURE_SHOW_DESCRIPTION:··return·true;

    Closing brace must be on a line by itself

    #56: ········case·FEATURE_USES_QUESTIONS:····return·true;

    Closing brace must be on a line by itself

    #58: ········default:························return·null;

    Closing brace must be on a line by itself

mod\exam\view.php

    #93: $attempted_attempt·=·exam_user_attempts($exam->id,·$USER->id);

    Variable "attempted_attempt" must not contain underscores.

    #99: $output·.=·html_writer::tag('p',·get_string('attempted',·'exam',·$attempted_attempt));

    Variable "attempted_attempt" must not contain underscores.

    #105: if·(($exam->attempts·==·0)·||·$attempted_attempt·<·$exam->attempts)·{

    Variable "attempted_attempt" must not contain underscores.

    #107: ····if·($attempted_attempt·>·0)·{

    Variable "attempted_attempt" must not contain underscores.

## 13 sept 2020 version   = 2020091303; // The current module version (Date: YYYYMMDDXX).
* 27 error(es) y 55 advertencia(s)
mod\exam\backup\moodle2\backup_exam_settingslib.php

    #1: <?php

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.
    End of line character is invalid; expected "\n" but found "\r\n"

mod\exam\backup\moodle2\backup_exam_stepslib.php

    #30: ·*···············(CL,pk->id)···························|·····

    Whitespace found at end of line

    #32: ·*·····················|·························exam_grades···

    Whitespace found at end of line

    #33: ·*·····················|··················(UL,·pk->id,fk->examid)····

    Whitespace found at end of line

    #34: ·*········································

    Whitespace found at end of line

mod\exam\db\caches.php

    #26: $definitions·=·array(

    Expected MOODLE_INTERNAL check or config.php inclusion. Change in global state detected.

mod\exam\db\uninstall.php

    #21: ·*·@copyright··2014·Pinky·Sharma·

    Whitespace found at end of line

mod\exam\lib.php

    #46: ········case·FEATURE_GRADE_HAS_GRADE:···return·true;

    Closing brace must be on a line by itself

    #47: ········case·FEATURE_GRADE_OUTCOMES:····return·true;

    Closing brace must be on a line by itself

    #48: ········case·FEATURE_GROUPS:············return·true;

    Closing brace must be on a line by itself

    #49: ········case·FEATURE_GROUPINGS:·········return·true;

    Closing brace must be on a line by itself

    #50: ········case·FEATURE_GROUPMEMBERSONLY:··return·true;

    Closing brace must be on a line by itself

    #51: ········case·FEATURE_MOD_INTRO:·········return·true;

    Closing brace must be on a line by itself

    #52: ········case·FEATURE_BACKUP_MOODLE2:····return·true;

    Closing brace must be on a line by itself

    #55: ········case·FEATURE_SHOW_DESCRIPTION:··return·true;

    Closing brace must be on a line by itself

    #56: ········case·FEATURE_USES_QUESTIONS:····return·true;

    Closing brace must be on a line by itself

    #58: ········default:························return·null;

    Closing brace must be on a line by itself

    #174: ····return·false;··//··True·if·anything·was·printed,·otherwise·false.

    Expected 1 space before comment text but found 2; use block comment if you need indentation

    #389: ····//$totalquestion·=·$DB->count_records('quiz_slots',·array('quizid'·=>·$exam->quizid));

    No space found before comment text; expected "// $totalquestion = $DB->count_records('quiz_slots', array('quizid' => $exam->quizid));" but found "//$totalquestion = $DB->count_records('quiz_slots', array('quizid' => $exam->quizid));"

mod\exam\mod_form.php

    #61: ········//$this->add_intro_editor();

    No space found before comment text; expected "// $this->add_intro_editor();" but found "//$this->add_intro_editor();"

mod\exam\pluginfile.php

    #22: ·*·@copyright··2014·Pinky·Sharma·

    Whitespace found at end of line

mod\exam\result.php

    #20: ·*·@package···mod_exam·

    Whitespace found at end of line

mod\exam\view.php

    #93: $attempted_attempt·=·exam_user_attempts($exam->id,·$USER->id);

    Variable "attempted_attempt" must not contain underscores.

    #99: $output·.=·html_writer::tag('p',·get_string('attempted',·'exam',·$attempted_attempt));

    Variable "attempted_attempt" must not contain underscores.

    #105: if·(($exam->attempts·==·0)·||·$attempted_attempt·<·$exam->attempts)·{

    Variable "attempted_attempt" must not contain underscores.

    #107: ····if·($attempted_attempt·>·0)·{

    Variable "attempted_attempt" must not contain underscores.


## 13 sept 202 to 14 sept 2020
* Replaced hard-coded English language strings by hard-coded Spanish language strings.
* Changed name to formativeMCquiz

## 11 Aug 2015 original code by original author
* forked from https://github.com/vidyamantra/moodle-mod_exam

