# /**
 * Get a list of users
 -> first user is your own account, remove from entire list
 -> generate own account data
 -> generate pagination data
 -> create frequency lists of skills and positions
 -> generate network feed + establish subscription status for each user (active, blocked, idle, pending) + set badge for most popular skill
 
 * On page change
 -> if new page is the same with current page DO NOTHING!
 -> clear current feed
 -> set new page as active
 -> generate network feed + establish subscription status for each user (active, blocked, idle, pending) + set badge for most popular skill
 
