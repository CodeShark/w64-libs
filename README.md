This repository contains prebuilt static libraries for crossbuilding to 64-bit Windows using mingw-w64.

Tools

copydiff - a tool to copy the set of files changed in a git repository between two commits
		to a particular location.

	Usage:		copydiff <commit 1> <commit 2> <location>

	Example:	copydiff HEAD^ HEAD /home/me/diff_files


install - a tool to untar a compressed library to a particular sysroot

	Usage:		install <library> <sysroot>

	Example:	install ../libs/mylib-1.2.3-dev /usr/x86_64-w64-mingw32

Disclaimer

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
	THE SOFTWARE.

