# libft Toolbox
All in one toolbox for functions commonly used in 42 projects
Does NOT follow libft 
Functions are continuously added

ft_printf added

## Character checking functions
| Function | Prototype | Description |
|---|---|---|
| ft_isalnum | int	ft_isalnum(int c) | check if alphanumeric |
| ft_isalpha | int	ft_isalpha(int c) | check if alphabet |
| ft_isascii | int	ft_isascii(int c) | check if ascii character|
| ft_isdigit | int	ft_isdigit(int c) | check if digit |
| ft_isprint | int	ft_isprint(int c) | check if printable char |
| ft_tolower | int	ft_tolower(int c) | eturns lowercase of the letter received |
| ft_toupper | int	ft_toupper(int c) | returns uppercase of the letter received |

## Character put functions (external file)
| Function | Prototype | Description |
|---|---|---|
| ft_putchar_fd | int	ft_putchar_fd(char c, int fd) | writes in character c |
| ft_putendl_fd | void	ft_putendl_fd(char *c, int fd) | writes in  string c with \n |
|  ft_putnbr_b_fd | int	ft_putnbr_b_fd( unsigned long nbr, char *base, int fd) | writes in int in a specfied base |
| fd_putnbr_fd | int	ft_putnbr_fd(int n, int fd) | writes in int n |
| ft_putstr_fd | int	ft_putstr_fd(char *c, int fd) | writes in  string s |
| ft_putunsignbr_fd | int	ft_putunsignbr_fd(unsigned long n, int fd) | writes in  unsigned int n |

## String manipulation functions 
| Function | Prototype | Description |
|---|---|---|
| ft_split | char	**ft_split(char const *s, char c) | splits string s using character c as delimiter 
| ft_strtrim | char	*ft_strtrim(char const *s1, char const *set) | returns string with characters in set trimmed from front & back |
| ft_strjoin | char	*ft_strjoin(char const *s1, char const *s2) | returns ptr to new string after  cat 2 strings |
| ft_substr | char	*ft_substr(char const *str, unsigned int start, size_t len) | returns pointer to substring from start, length of len |

## String conversion functions
| Function | Prototype | Description |
|---|---|---|
| ft_atoi | int	ft_atoi(const char *str) | Converts str to int |
| ft_itoa | char	*ft_itoa(int n) | Convert int to str |

## String search functions
| Function | Prototype | Description |
|---|---|---|
| ft_strchr | char	*ft_strchr(const char *str, int c) | returns pointer to the first occurence of c |
| ft_strrchr | char	*ft_strrchr(const char *str, int c) | returns pointer to the last occurence of c |
| ft_strnstr | char	*ft_strnstr(const char	*str, const char *to_find, size_t len) | looks for to_find in str in the first len chars |

## Unsorted
| Function | Prototype | Description |
|---|---|---|
| ft_bzero | void	ft_bzero(void *str, size_t n) | writes n bytes of string with null |
| ft_calloc | void	*ft_calloc(size_t num, size_t size) | alloc memory, set to 0 |
| ft_memchr | void	*ft_memchr(const void *str, int c, size_t n) | returns pointer to the first occurence of c |
| ft_memcmp | int	ft_memcmp(const void *str1, const void *str2, size_t n) | compares first n characters for 2 strings. Returns first diff |
| ft_memcpy | void	*ft_memcpy(void *dest, const void *src, size_t n) | copies the first n chars from src to dest with no overlap. |
| ft_memmove | void	*ft_memmove(void *dest, const void *src, size_t n) | copies n bytes of src into dest. Memory location can overlap |
| ft_memset | void	*ft_memset(void *str, int c, size_t n) | replaces first n bytes of a string with character c |
| ft_printf | int	ft_printf(const char *str, ...) | printf without bonus|
| ft_strdup | char	*ft_strdup(const char *src) | duplicates a string |
| ft_striteri | void	ft_striteri(char *s, void (*f)(unsigned int, char*)) | applies func f to each character in string s |
| ft_strlcat | size_t	ft_strlcat(char *dest, const char *src, size_t size) | Cats size - 1 chars from src to dest with null added |
| ft_strlcpy | size_t	ft_strlcpy(char *dest, const char *src, size_t size) | Copies up to size - 1 fr src to dest. Null ended. |
| ft_strlen | size_t	ft_strlen(const char *str) | returns number of character in a string |
| ft_strmapi | char	*ft_strmapi(char const *s, char (*f)(unsigned int, char)) | applies func f to each character in string s |
| ft_strncmp | int	ft_strncmp(const char *s1, const char *s2, size_t n) | compares first n characters for 2 strings. |


 



## Linked List
 | Function | Prototype | Description |
|---|---|---|
| ft_lstadd_back | void	ft_lstadd_back(t_list **lst, t_list *new) | adds element new back of the list |
| ft_lstadd_front | void	ft_lstadd_front(t_list **lst, t_list *new) | adds element new in front of list. Moves lst to the front |
| ft_lstclear | void	ft_lstclear(t_list **lst, void (*del)(void*)) | delete entire list pointed by lst |
| ft_lstdelone | void	ft_lstdelone(t_list *lst, void (*del)(void*)) | deletes content pointed by lst |
| ft_lstiter | void	ft_lstiter(t_list *lst, void (*f)(void*)) | iterates function f on content of each element |
| ft_lstlast | t_list	*ft_lstlast(t_list *lst) | traverses the list till null and returns the last node |
| ft_lstmap | t_list	*ft_lstmap(t_list *lst, void *(*f)(void*), void(*del)(void*)) | iterates function f on content of each element |
| ft_lstnew | t_list	*ft_lstnew(void *content) | creates and returns a new element with content |
| ft_lstsdize | int	ft_lstsize(t_list *lst) | traverses the list till null and returns the size |

 

 
 


 







