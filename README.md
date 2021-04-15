# MAKEALL6
A batch file to make all 6 man endgame tablebases for Chessmaster using the FEG version 3.03c, get FEG from here: http://kirill-kryukov.com/chess/discussion-board/viewtopic.php?t=9670</br>
Ensure that you have generated all the 3,4, and 5 man tablebases.
Put this batch file in your FEG folder (ensure your drive has enough space - I'm not sure how much is needed, but a few Tb should suffice).
Then run the batch file and leave your computer on for about a month and a half.
This was possible using the log files from Juan P. Naar found here: http://talkchess.com/forum3/viewtopic.php?f=2&t=74130</br>
Remember to stop Windows update from restarting your computer: 
Press the Windows key and type gpedit.msc</br>
Press Enter.</br>
Local Group Policy Editor>Computer Configuration>Administrative Templates>Windows Components>Windows Update</br>
Change “No auto-restart with automatic installations of scheduled updates” to enabled.
