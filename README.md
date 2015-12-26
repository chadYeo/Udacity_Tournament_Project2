# Udacity_Tournament_Project2
Udacity Full Stack Web Developer Nanodegree Project 2 - Tournament Results

<h2>Files</h2>
 - tournament.py - Implementation of a Swiss-system tournament
 - tournament.sql - Table definition for the tournament project
 - tournament_test.py - Test cases for tournament.py

<h2>Usage</h2>
 - Use Vagrant VM
 - Check the database called tournament
 - vagrant@vagrant-ubuntu-trusty-32:/vagrant/tournament$ 

<h2>Run Test</h2>
  vagrant@vagrant-ubuntu-trusty-32:/vagrant/tournament$ python tournament_test.py
  1. Old matches can be deleted.
  2. Player records can be deleted.
  3. After deleting, countPlayers() returns zero.
  4. After registering a player, countPlayers() returns 1.
  5. Players can be registered and deleted.
  6. Newly registered players appear in the standings with no matches.
  7. After a match, players have updated standings.
  8. After one match, players with one win are paired.
  Success!  All tests pass!
